#### Test 54312298c831015_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Waited long enough for: ServiceRecord{43fd32b8 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
I/SensorManager(  906): mEventCount = 1350
E/cutils-trace( 4421): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4421): ====startRecUseTime====
D/htc.customization.log.level( 4421):  is 
W/CustomizationLogLevel( 4421): Level value is invalid, use default level 2
D/CustomizationManager( 4421):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4421): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4421): Parsing tag category name = system
I/CustomizationCIDLoader( 4421): Parsing tag category name = application
I/CustomizationCIDLoader( 4421): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4421): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4421): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4421): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4421): Parsing tag category name = Settings
D/CustomizationManager( 4421):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4421):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4421): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4421): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4421): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4421): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4421
D/PMS     (  906): acquireHCC(422c74f0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(420b6a90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x62d21448 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1110383472
I/FeedHostManager( 1266): [onPause]
I/FeedProviderManager( 1266): onPause
I/FeedHostManager( 1266): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b40da8
I/SocialFeedProvider( 1266): +onPause
I/SocialFeedProvider( 1266): -onPause
D/PMS     (  906): acquireWL(42100350): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4432 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1266): [trimMemory] 20
W/asset   ( 4432): Copying FileAsset 0x5c7f9428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4432): Binding Chromium to main looper Looper (main, tid 1) {41a94738}
I/LibraryLoader( 4432): Expected native library version number "",actual native library version number ""
I/chromium( 4432): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4432): Initializing chromium process, renderers=0
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4249e9f0:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4432): 1101701488: getState(). Returning 12
D/PMS     (  906): acquireWL(4241e0e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(42142760): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(4241e0e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4432): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4432): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4432): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4432): Local Branch: 
I/Adreno-EGL( 4432): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4432): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4432):                  aa63bbd948f41d15fc72f585e
W/chromium( 4432): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4432): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4432): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4432): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4432): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4432): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4432): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4432): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4432): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4432): CordovaWebView is running on device made by: HTC
,W/AwContents( 4432): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1266
,W/ResourceType( 4432): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4432): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41adb820, mServedView=org.apache.cordova.engine.SystemWebView{41aa1488 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=4432
,W/AwContents( 4432): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +270ms
,D/PMS     (  906): releaseWL(42100350): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4432): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4432): JniHelper::setJavaVM(0x41568048), pthread_self() = 1662213856
,D/JX-Cordova( 4432): jxcore cordova android initializing
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 11.564MB for 96598-byte allocation
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 11.623MB for 144892-byte allocation
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 11.725MB for 217334-byte allocation
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 11.901MB for 325996-byte allocation
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 12.175MB for 488990-byte allocation
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 13.182MB for 1100216-byte allocation
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 14.075MB for 1650320-byte allocation
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 15.443MB for 2475476-byte allocation
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 17.472MB for 3713210-byte allocation
,W/jxcore-log( 4432): Initializing JXcore engine
,W/jxcore-log( 4432): JXcore engine is ready
,W/jxcore-log( 4432): Starting JXcore engine
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(422c74f0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(420b6a90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4432): Platform android
W/jxcore-log( 4432): 
,W/jxcore-log( 4432): Process ARCH arm
W/jxcore-log( 4432): 
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4475 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(42575858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{41c71950: PendingIntentRecord{41fd7598 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450738880086, Int=60000
,D/PMS     (  906): releaseWL(42575858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4475): SMSBackupAgentService started
,D/SMSBackup( 4475): Checking restore status
D/SMSBackup( 4475): Restore complete
,D/SMSBackup( 4475): cancelCheckAlarm
,D/SMSBackup( 4475): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3633
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3633:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3633
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(424ec6c0): PARTIAL_WAKE_LOCK  Icing 0x1 2264 10028 null
,D/PMS     (  906): releaseWL(424ec6c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(423eb2f0): PARTIAL_WAKE_LOCK  Icing 0x1 2264 10028 null
,I/jxcore-log( 4432): JXcore Cordova bridge is ready!
I/jxcore-log( 4432): 
,W/jxcore-log( 4432): JXcore engine is started
,I/chromium( 4432): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  906): releaseWL(423eb2f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42215508): PARTIAL_WAKE_LOCK  Icing 0x1 2264 10028 null
,D/PMS     (  906): releaseWL(42215508): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): releaseWL(42142760): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4432): Toggling radios to true
I/jxcore-log( 4432): 
,D/BluetoothAdapter( 4432): enable(): BT is already enabled..!
,D/WifiManager( 4432): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1346
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
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
,D/WifiManager( 4432): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4432): reconnect: Base Package Name=com.test.thalitest, uid=10348
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): TDLS: Tear down peers
,I/wpa_supplicant( 1166): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4432): Radios toggled
I/jxcore-log( 4432): 
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4432): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4432): 
D/WifiService(  906): setWifiEnabled: true pid=4432, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  906): New client listening to asynchronous messages
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4432): Perf Test app loaded loaded
I/jxcore-log( 4432): 
I/Choreographer( 4432): Skipped 77 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4432): check test folder
I/jxcore-log( 4432): 
,I/jxcore-log( 4432): found test : ./testFindPeers.js
I/jxcore-log( 4432): 
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1166): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1166): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1166): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/Tethering(  906): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb83f3bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1166):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1166): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1166): send_and_recv ,error 0 - cmd 18
I/wpa_supplicant( 1166): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1166): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(42522bd0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
I/jxcore-log( 4432): found test : ./testSendData.js
I/jxcore-log( 4432): 
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19471 mDataStallAlarmIntent=PendingIntent{42076f98: PendingIntentRecord{422bccc8 android broadcastIntent}}
D/wpa_supplicant( 1166): Fast associate: Old scan results
I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,D/WISPrService( 4211): >>>>>WISPrService start isConnected = false<<<<<
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906):    returned true
,D/WISPrService( 4211): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiService(  906): New client listening to asynchronous messages
,W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
,D/ConnectivityService(  906): resetConnections(wlan0, 3)
,D/PMS     (  906): acquireWL(439f1598): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10028 null
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/PMS     (  906): acquireWL(42dd7878): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10028 null
D/libc    (  364): [NET] entry_id:5   entry:0xb70edc20  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb70f6c68  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb70f2478  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb70f22f8  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb70f6d78  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb70f6f50  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  906): releaseWL(42dd7878): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/jxcore-log( 4432): found test : ./testSendData2.js
I/jxcore-log( 4432): 
,D/WISPrService( 4211): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4211): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/jxcore  ( 4432): Error!: missing ) after argument list
E/jxcore  ( 4432): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(4401ab30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,I/chromium( 4432): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1358/10028)
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SCAN
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
D/PMS     (  906): releaseWL(4401ab30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  906): releaseWL(439f1598): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/PMS     (  906): acquireWL(437bb968): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1917/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3928/10154)
,I/NetworkMonitor( 3928): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1266): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1432/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1266/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.,
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4321/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4321/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2466/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4501 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4501): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4501): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4501): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4501): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4501): Preparing secondary program dexes.
V/DexLibLoader( 4501): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4501): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4501): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4501): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4501): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4501): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4501): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4501): Dex already copied
D/OdexVerifier( 4501): Odex verification is skipped.
,V/DexLibLoader( 4501): Creating class loader
,V/DexLibLoader( 4501): Finished creating class loader
V/DexLibLoader( 4501): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4501): Dex already copied
D/OdexVerifier( 4501): Odex verification is skipped.
V/DexLibLoader( 4501): Creating class loader
,V/DexLibLoader( 4501): Finished creating class loader
V/DexLibLoader( 4501): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4501): Dex already copied
D/OdexVerifier( 4501): Odex verification is skipped.
,V/DexLibLoader( 4501): Creating class loader
V/DexLibLoader( 4501): Finished creating class loader
V/DexLibLoader( 4501): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4501): Dex already copied
,D/OdexVerifier( 4501): Odex verification is skipped.
,V/DexLibLoader( 4501): Creating class loader
V/DexLibLoader( 4501): Finished creating class loader
,V/DexLibLoader( 4501): Verifying classes from secondary dexes.
,D/DexLibLoader( 4501): DexLibLoader.ensureDexLoaded took 18 ms
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): releaseWL(437bb968): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/dalvikvm( 4501): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4501): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4501): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4501): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4501): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4501): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4501): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4501): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4501): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1166): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1166): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1166): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1166): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1166): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 3
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 1
I/wpa_supplicant( 1166): wpa_s->is_screen_on 1
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): selected network = 1
D/wpa_supplicant( 1166): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb83f54e8  current_ssid=0x0
D/wpa_supplicant( 1166): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1166): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1166): TDLS: TDLS is allowed in the tar,get BSS
I/wpa_supplicant( 1166): check if in concurrent case
I/wpa_supplicant( 1166): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1166): RSN: PMKSA cache search - network_ctx=0xb83f54e8 try_opportunistic=0
D/wpa_supplicant( 1166): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1166): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1166): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1166): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1166): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1166): nl80211: Unsubscribe mgmt frames handle 0xb83f4718 (mode change)
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1166): nl80211: Subscribe to mgmt frames with non-AP handle 0xb83f4718
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb83f4718
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb83f4718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb83f4718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb83f4718
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb83f4718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb83f4718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb83f4718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb83f4718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb83f4718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb83f4718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1166):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1166):   * freq=2412
D/wpa_supplicant( 1166):   * Auth Type 0
D/wpa_supplicant( 1166):   * WPA Versions 0x2
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1166): nl80211: Connect request send successfully
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 -, cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1166): reply (498) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-48
I/wpa_supplicant( 1166): tsf=0000000107981123
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-50
I/wpa_supplicant( 1166): tsf=0000000107981140
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-50
I/wpa_supplicant( 1166): tsf=0000000107981136
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-88
I/wpa_supplicant( 1166): tsf=0000000107981144
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=UPC4688432
I/wpa_supplicant( 1166): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 107981123, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 107981140, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 107981136, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 107981144, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4501): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1166): nl80211: Connect event
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1166): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1166): Add randomness: count=9 entropy=4
I/wpa_supplicant( 1166): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1166): TDLS: Remove peers on association
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1166): EAPOL: enable timer tick
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1166): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1166): Get randomness: len=32 entropy=5
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412,
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,I/wpa_supplicant( 1166): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb83f49f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1166):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): This record is existed, only update it...
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1166): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ec9b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1166):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1166): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1166): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1166): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1166): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1166): set send_ind_to_ndc = 0
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1166): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1166): EAPOL authentication completed successfully
I/wpa_supplicant( 1166): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/Tethering(  906): [isWifi] getHotspotEnabled: false,
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...,
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/WISPrService( 4211): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4211): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 1
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
,D/PMS     (  906): acquireWL(439872a8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/WifiNative-wlan0(  906):    returned null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42527940 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42527940 target=com.android.internal.util.StateMachine$SmHandler }
,W/fb4a(:<default>):StaticBindingVerifier( 4501): Verify
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4501): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4501): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/SensorManager(  906): mEventCount = 1500
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3888
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3888:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  906): acquireWL(4324b5f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2264 10028 null
I/ActivityManager(  906): Recipient 3888
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4363fd40): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2264 10028 null
,D/PMS     (  906): releaseWL(4324b5f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2264/10028)
,D/GCM     ( 1358): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2264/10028)
,D/PMS     (  906): releaseWL(4363fd40): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1393): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4530 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1393/10053)
,D/AutoSetting( 1393): Util - no network available!
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1393/10053)
D/AutoSetting( 1393): service - onCreate()
D/AutoSetting( 1393): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  906): request 422adb20 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1393): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1393): service - mHandler: cancel location update
D/AutoSetting( 1393): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4501): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4501): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4501): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4530): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4530): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4530): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4530): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4546 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4530/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4530/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4530/10078)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4501): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/Process (  906): killProcessQuiet, pid=4265
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4570 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 4265:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4265
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 9.967MB for 84664-byte allocation
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4570): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4570): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 9.982MB for 28144-byte allocation
E/dalvikvm( 4501): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4501): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;,
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4501): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4501): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4501): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4501): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4501): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4501): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4501): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4501): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4501): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4501): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4501): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4501): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4501): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4501): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4501): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4501): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/GAV2    ( 4570): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4570): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4570): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 10.030MB for 39954-byte allocation
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(439872a8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
I/dalvikvm-heap( 4501): Grow heap (frag case) to 10.107MB for 79892-byte allocation
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -49, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19473 delay=15s
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 4211): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@423c1d00
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
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
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1111): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  906): acquireWL(43fbb298): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4530/10078)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43e86a58): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2264 10028 null
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
D/PMS     (  906): releaseWL(43fbb298): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4570/10151)
D/PMS     (  906): acquireWL(4366f000): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2264 10028 null
D/PMS     (  906): releaseWL(43e86a58): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2264/10028)
I/logwrapper(  364): /system/bin/ip terminated by exit(254)
I/CheckinService( 2264): Preparing to send checkin request
I/EventLogService( 2264): Accumulating logs since 1450738832198
V/WebViewChromiumFactoryProvider( 4570): Binding Chromium to main looper Looper (main, tid 1) {41a99428}
I/LibraryLoader( 4570): Expected native library version number "",actual native library version number ""
I/chromium( 4570): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4570): Initializing chromium process, renderers=0
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  906): acquireWL(43ec9a88): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(43fa3b60): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4570): BLUETOOTH permission is missing!
,I/GoogleHttpClient( 2264): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2264): Using GMS GoogleHttpClient
D/PMS     (  906): releaseWL(43ec9a88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4570): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4570): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4570): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4570): Local Branch: 
I/Adreno-EGL( 4570): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4570): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4570):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2264/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2264/10028)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/dalvikvm-heap( 4501): Grow heap (frag case) to 10.289MB for 75760-byte allocation
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e4f220 u0 ReceiverList{43e4f100 4501 com.facebook.katana/10026/u0 remote:43b9d500}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e4f220 u0 ReceiverList{43e4f100 4501 com.facebook.katana/10026/u0 remote:43b9d500}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43fb1ce8 u0 ReceiverList{43fb1c88 4501 com.facebook.katana/10026/u0 remote:43f4e3f8}}
,I/NSApplication( 4570): Starting up...
,W/GLSUser ( 1358): GoogleAccountDataService.getToken()
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4570/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4570/10151)
,W/GLSActivity( 1358): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1358): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1358): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  906): acquireWL(4323d188): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1432 10028 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/PMS     (  906): releaseWL(4323d188): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
,D/Process (  906): killProcessQuiet, pid=4030
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Killing 4030:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
,D/GCoreFlp( 1432): Unknown pending intent to remove.
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
D/PMS     (  906): acquireWL(43ac1dc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1432 10028 null
,D/PMS     (  906): releaseWL(43ac1dc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/GCM     ( 1358): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
,D/wpa_supplicant( 1166): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1166): EAPOL: disable timer tick
,I/ActivityManager(  906): Recipient 4030
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4501): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/DotMatrix( 1580): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4501): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/RemoteViews( 1111): com.google.android.gms (false,0)
W/CheckinRequestBuilder( 2264): awaiting user notification for token
D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41a8ce80 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1111): com.google.android.gms 1 6 2 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4641 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4641): install
,I/MultiDex( 4641): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4641): loading existing secondary dex files
,I/MultiDex( 4641): load found 1 secondary dex files
,I/MultiDex( 4641): install done
,I/ProviderInstaller( 4641): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4641): Local Branch: 
I/Adreno-EGL( 4641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4641):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4641): Local Branch: 
I/Adreno-EGL( 4641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4641):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1111): WifiActivity: 3
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): releaseWL(42522bd0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(43659588): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(43659588): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1266): [onReceive] WIFI(1): CONNECTED
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3928/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43266658): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4530/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1432/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4321/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1917/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1266/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3949/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/acms    ( 1917): Checking Certificates
I/acms    ( 1917): Checking Developer Certificates
I/acms    ( 1917): Checking Application Certificates
I/acms    ( 1917): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1917): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1917): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1917): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1917): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1917): Updating next query delay: 75600000
I/mlserverapp( 1917): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1917): cancelACMSProgrammedChecks
I/NetworkMonitor( 3928): type=WIFI subType= reason=null isConnected=true
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  906): Found interface wlan0
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4321/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
D/PMS     (  906): releaseWL(43266658): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2466/10021)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(431edc90): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2264 10028 null
D/PMS     (  906): releaseWL(431edc90): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1358): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1358): [NET] getaddrinfo-,err=8
D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1358): [NET] getaddrinfo-, 1
,D/libc    ( 1358): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =11bc +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2264/10028)
D/PMS     (  906): acquireWL(42db0a78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1358 10028 null
,D/AutoSetting( 1393): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4530): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4530): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1393/10053)
,D/AutoSetting( 1393): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1393): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1393): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1393): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1393): service - handleMessage() setting current location null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4570/10151)
D/AutoSetting( 1393): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1393): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1393/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 268
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1358): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 13.507MB for 1821008-byte allocation
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42166010
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42166010, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42196c20
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42578068
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  906): Going to sleep due to screen timeout...
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1358): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/PMS     (  906): acquireWL(4244da68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10028 null
D/PMS     (  906): releaseWL(4244da68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4641/10028)
,D/GCM     ( 1358): Connected
D/PMS     (  906): acquireWL(43281aa8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/PMS     (  906): releaseWL(42db0a78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1358/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/PMS     (  906): releaseWL(43281aa8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(430de1f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1358/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1358): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1358/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/PMS     (  906): acquireWL(43249150): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10028 null
D/PMS     (  906): releaseWL(430de1f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): releaseWL(43249150): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4641): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4641): Local Branch: 
I/Adreno-EGL( 4641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4641):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 2264): Sending checkin request (9004 bytes)
D/libc    ( 2264): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2264): [NET] getaddrinfo-,err=8
D/libc    ( 2264): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2264): [NET] getaddrinfo-, 1
,D/libc    ( 2264): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =918e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 239
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2264): [NET] getaddrinfo_proxy-, success
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 373ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1252): ScreenObserver: OFF
,D/NfcService( 1252): applyRouting - 0,
D/NfcService( 1252): applyRouting -2,
V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@430a5bd8)
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  906): Disable input method client, pid=4432
D/PMS     (  906): acquireWL(425291d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
W/ResourceType( 4432): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4432): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aa1488 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1111): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****,
D/PMS     (  906): releaseWL(425291d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  906): wakingUp
I/WindowManager(  906): No lock screen! windowToken=null
D/libc    ( 2264): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2264): [NET] getaddrinfo-,err=8
D/PMS     (  906): acquireWL(43248758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMN     (  906): onScreenOn
D/PMS     (  906): releaseWL(43248758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2466): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1252): applyRouting - 0
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
D/MtpService( 2466): [MTP][onReceive]-
D/AutoSetting( 1393): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1252): applyRouting -2
D/PMS     (  906): acquireWL(43235128): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
,D/PMS     (  906): releaseWL(43235128): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AutoSetting( 1393): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/ClockThread( 1111): stop update clock
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
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
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19474 delay=15s
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:On
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 4211): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4211): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4211): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4211): Cust_ConnectToPC   : spcsc>false
D/        ( 4211): Cust_ConnectToPC   : IPT>true
D/        ( 4211): Cust_ConnectToPC   : Singel_USB>false
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=6 [16][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
V/SRS_Proc(  371): ParamSet string: screen_state=on
W/Settings( 4211): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
E/SmartNS_Utility( 4211): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4211): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4211): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  906):    returned true
I/PSReceiver( 4211): onReceive:android.intent.action.USER_PRESENT
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/NetworkPolicy(  906): updateScreenOn: false
I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
I/SmartNS_PSService( 4211): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4211): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4211):  defaultType:0
W/ContextImpl( 4211): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4681 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(43afda08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1432 10028 null
D/PMS     (  906): releaseWL(43afda08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1821): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1821): onScreenOn: 1450738886892
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1821): onScreenOn: 1450738886892
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42196c20
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42196c20, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42578068
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(425643f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=25 [4][1][0]
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19474 mDataStallAlarmIntent=PendingIntent{439e3350: PendingIntentRecord{422bccc8 android broadcastIntent}}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/PMS     (  906): releaseWL(425643f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:Off
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1166): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(431e7398): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  906): updateScreenOn: false
D/PMS     (  906): acquireWL(43247dd0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4681 1000 null
,D/PMS     (  906): releaseWL(431e7398): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(43247dd0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4681): getMobilePolicyEnabled, result = true
,D/Process (  906): killProcessQuiet, pid=4291
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4291:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Recipient 4291
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4681): getMobilePolicyEnabled, result = true
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
D/WifiService(  906): New client listening to asynchronous messages
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42578068
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/dalvikvm( 4432): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42578068, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42578068, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42578068
,W/dalvikvm( 4432): threadid=1: thread exiting with uncaught exception (group=0x41660e30)
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42584870 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42584870 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,E/AndroidRuntime( 4432): FATAL EXCEPTION: main
E/AndroidRuntime( 4432): Process: com.test.thalitest, PID: 4432
E/AndroidRuntime( 4432): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4432): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4432): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4432): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4432): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4432): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4432): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4432): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4432): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4432): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4432): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4432): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4432): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4432): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4432): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4432): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4432): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4432): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4432): 	at dalvik.system.NativeStart.main(Native Method)
E/ActivityManager(  906): App crashed! Process: com.test.thalitest
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] getTotalRam: 1873 Mb
W/ActivityManager(  906):   Force finishing activity com.test.thalitest/.MainActivity
D/PMS     (  906): acquireWL(43fb3ed0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1432 10028 null
D/PMS     (  906): releaseWL(43fb3ed0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1821): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1821): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1821): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1821): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1821): onScreenOff
,D/Process ( 4432): killProcess, pid=4432
D/Process ( 4432): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/Process (  906): killProcessQuiet, pid=4321
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1393): service - mHandler: cancel location update
,D/AutoSetting( 1393): service -           changes count: 0
I/ActivityManager(  906): Killing 4321:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4321
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  906): channel '42417e60 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  906): channel '42417e60 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/ActivityManager(  906): Recipient 4432
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '42417e60 com.test.thalitest.MainActivity (s)'
I/ActivityManager(  906): Process com.test.thalitest (pid 4432) has died.
I/WindowManager(  906): WINDOW DIED Window{42417e60 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/WindowManager(  906): Failed looking up window
W/WindowManager(  906): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@43e8fe58 does not exist
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  906): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  906): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  906): WIN DEATH: null
D/PMS     (  906): acquireWL(43f4e208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10028 null
D/PMS     (  906): releaseWL(43f4e208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2264/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2264/10028)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=33 [3][1][0]
,W/Binder  ( 1206): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1206): java.lang.NullPointerException
W/Binder  ( 1206): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1206): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1206): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1206): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4432 uid 10348
,W/GLSUser ( 1358): GoogleAccountDataService.getToken()
,W/GLSActivity( 1358): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1358): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1358): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1580): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2264): awaiting user notification for token
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41e018a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 13 4 12
,I/CheckinTask( 2264): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2264): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2264/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2264/10028)
,D/PMS     (  906): releaseWL(4366f000): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 2264): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cc9c88 that was originally bound here
E/ActivityThread( 2264): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cc9c88 that was originally bound here
E/ActivityThread( 2264): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2264): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2264): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2264): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2264): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2264): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2264): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2264): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2264): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2264): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2264): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2264): 	at bks.a(SourceFile:298)
E/ActivityThread( 2264): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2264): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2264): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2264): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1358): GCM config loaded
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,W/fb4a(:<default>):UserScope( 4501): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4501): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4501): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4501/10026)
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =176e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  906): releaseWL(43fa3b60): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4570): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(43aeebb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1432 10028 null
,D/PMS     (  906): acquireWL(43af3020): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1432 10028 null
,D/PMS     (  906): releaseWL(43aeebb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(43af3020): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/AutoSetting( 1514): service - handleMessage() stop self
,D/AutoSetting( 1514): service - onDestroy() END
,D/AutoSetting( 1514): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4344
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4344:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4344
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{430d0468 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(435acfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(435acfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1393): service - mHandler: update timezone
,D/AutoSetting( 1514): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1514): service - onCreate()
,D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1514): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1580): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1514): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1514): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1514): service - mHandler: update timezone
,D/AutoSetting( 1514): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1514): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1514): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1514): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1580): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1111): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41e782d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.htc.htclocationservice 2 8 2 11
,D/AutoSetting( 1393): service - handleMessage() stop self
,D/AutoSetting( 1393): service - onDestroy() END
,D/AutoSetting( 1393): service - handleMessage() quit looper
D/PMS     (  906): acquireWL(436661c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
V/AlarmManager(  906): sending alarm PendingIntent{43ab8140: PendingIntentRecord{4250fda0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140850, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4246f530: PendingIntentRecord{42466950 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140968, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
,D/PMS     (  906): acquireWL(43ed2930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10028 null
,D/PMS     (  906): releaseWL(43ed2930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(43f12228): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(436661c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =341 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 50
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): acquireWL(43fa13a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fa13a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43f84698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=143779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f84698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(43f12228): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  906): killProcessQuiet, pid=3949
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3949:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  906): Recipient 3949
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43bc14e8 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1514): service - handleMessage() stop self
,D/AutoSetting( 1514): service - onDestroy() END
,D/AutoSetting( 1514): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4308
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  906): Killing 4308:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/ActivityManager(  906): Recipient 4308
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(43a9a590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43a9a590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43a88ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=203780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a88ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43a2d398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4365e0e8: PendingIntentRecord{43859660 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228967, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4721 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{41df4ec8: PendingIntentRecord{41debd58 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450738996195, Int=10800000
,D/PMS     (  906): releaseWL(43a2d398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4721/10047)
,D/Process (  906): killProcessQuiet, pid=4361
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4361:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4361
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2264/10028)
,D/PMS     (  906): acquireWL(436577e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43efbf78: PendingIntentRecord{43a64d48 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=230429, Int=120000
,V/AlarmManager(  906): sending alarm PendingIntent{43a1afe8: PendingIntentRecord{43859660 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230706, Int=0
,D/PMS     (  906): releaseWL(436577e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43484518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43484518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(4343d958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=263779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4343d958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4338b790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4338b790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4327ecd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=323779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4327ecd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4327d930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{4309f310: PendingIntentRecord{430a55a0 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1450739135619, Int=0
,D/PMS     (  906): releaseWL(4327d930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 2264): No account for auth token provided
,D/libc    ( 2264): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2264): [NET] getaddrinfo-,err=8
D/libc    ( 2264): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2264): [NET] getaddrinfo-, 1
,D/libc    ( 2264): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c348 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2264): [NET] getaddrinfo_proxy-, success
I/global  ( 2264): call createSocket() return a new socket.
D/libc    ( 2264): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2264): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 2264): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2264): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2264/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2264/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2264/10028)
,W/GLSUser ( 1358): GoogleAccountDataService.getToken()
,W/GLSActivity( 1358): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1358): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1358): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1580): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1358): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1358): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1358): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1358): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1358): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1358): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1358): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1358): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41e78678 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4151): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4151): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4151): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4151): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4151): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4151): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4151): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4151): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1111): com.google.android.gms 2 14 4 12
,D/libc    ( 4151): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4151): [NET] getaddrinfo-,err=8
D/libc    ( 4151): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4151): [NET] getaddrinfo-, 1
,D/libc    ( 4151): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a295 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4151): [NET] getaddrinfo_proxy-, success
,I/global  ( 4151): call createSocket() return a new socket.
D/libc    ( 4151): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4151): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4151): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4151): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(4321ef20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4321ef20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(4321c5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=383779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4321c5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process (  906): killProcessQuiet, pid=4378
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4378:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4378
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(432175e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(432175e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43216798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=443779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43216798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(430b2a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430b2a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(425134f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=503780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425134f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42304a78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43650260: PendingIntentRecord{43a64d48 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=530714, Int=300000
,D/PMS     (  906): releaseWL(42304a78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(41f5a2e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41f5a2e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41cf3fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=563779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41cf3fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41dc0870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41dc0870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): start background delete task...
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,D/PMS     (  906): acquireWL(42ee0548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42ee0548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41ac4d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=623780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41ac4d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42629378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42629378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4241e070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=683780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4241e070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41cbc890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41cbc890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(431decc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=743780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(431decc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425181b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425181b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42375b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=803780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42375b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42407530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42407530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43656360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=863779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43656360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42480750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42480750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4219b650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=923779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4219b650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4366bcf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41d1bf58: PendingIntentRecord{423cc4b8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786480, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4239a168: PendingIntentRecord{423608e8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450739716490, Int=900000
,W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): releaseWL(4366bcf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageService( 4681): call getInstance()
D/PowerUsageList:PowerUsageHelper( 4681): MY_DEBUG = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(425b2910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425b2910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42503e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=983780, Int=0
,D/PMS     (  906): releaseWL(42503e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f9c050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{4323e990: PendingIntentRecord{42525bc0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1010221, Int=0
,D/PMS     (  906): acquireWL(43bacd48): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1358 10028 null
V/AlarmManager(  906): sending alarm PendingIntent{42447d90: PendingIntentRecord{436578b0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450739787021, Int=0
,D/PMS     (  906): releaseWL(43bacd48): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(43f49e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10028 null
D/PMS     (  906): releaseWL(43f49e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SmartSyncScreenOnOffTimeReceiver( 4681): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4681): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 20, nEnd = 23, bNormalRange = true
D/PMS     (  906): acquireWL(425e1138): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4681 1000 null
D/PMS     (  906): releaseWL(43f9c050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4681): [updateNmRange] new USERNIGHT_TIMESTART = 20, new USERNIGHT_TIMEEND = 23
,I/FeedHostManager( 1266): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
D/SmartSyncScreenOnOffTimeReceiver( 4681): AlarmOnTime = -1
,I/FeedHostManager( 1266): NightMode begin at 0, end at 7
D/SmartSyncScreenOnOffTimeReceiver( 4681): SettingOnTime = 1450821600000, randomSettingOnTime = 1450819668000
,D/SmartSyncScreenOnOffTimeReceiver( 4681): SettingOffTime = 1450810800000, randomSettingOffTime = 1450812979000
,D/SmartSyncScreenOnOffTimeReceiver( 4681): bDayMode = false
,D/PMS     (  906): acquireWL(42b442d8): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1266 10075 null
D/SmartSyncScreenOnOffTimeReceiver( 4681): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4681): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(425e1138): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(437dd3b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10075}
,I/FeedHostManager( 1266): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1450739787174, BeginTime: 1450738800000, EndTime: 1450764000000
V/AlarmManager(  906): sending alarm PendingIntent{41ebc1d8: PendingIntentRecord{434a1d70 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1450738800000, Int=0
,I/FeedHostManager( 1266): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
D/PMS     (  906): releaseWL(42b442d8): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  906): acquireWL(43f00ca0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1266 10075 null
D/PMS     (  906): releaseWL(43f00ca0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  906): releaseWL(437dd3b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
,D/PMS     (  906): acquireWL(43f2ef30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10028 null
,D/GCM     ( 1358): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1358/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/PMS     (  906): acquireWL(430a8ee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10028 null
D/PMS     (  906): releaseWL(43f2ef30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): releaseWL(430a8ee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100,
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=5 [136][7][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(430cf618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430cf618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43ee3d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1043779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ee3d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f3f6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43f3f6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(440151e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440151e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43fda578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1103779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43fda578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fcbf58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(43fcbf58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43eed508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43eed508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null,
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b9a2f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1163780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b9a2f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b81b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b81b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43b6b3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1223779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b6b3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b64ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b64ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43a99088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1283779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a99088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43a64c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43a64c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43a64088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1343779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a64088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43a31500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43a31500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(436689f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436689f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43662fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1403780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43662fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4365bd10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4365bd10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4324eba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4324eba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4324b2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1463779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4324b2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43246730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(43246730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43214ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43214ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,D/TetherSettings( 4211): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4211): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4211): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4211): Cust_ConnectToPC   : spcsc>false
D/        ( 4211): Cust_ConnectToPC   : IPT>true
,D/        ( 4211): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4211): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4211): Index of the first 1 = 3
,W/Settings( 4211): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4211): hasRemovableStorageSlot: true
W/ContextImpl( 4211): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/ContextImpl( 4211): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4211): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4211): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4211): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4236b228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1523780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4236b228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41f8d9e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41f8d9e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1111): closing low battery warning: level=100
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null,
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41dffe38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41dffe38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(424c5940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1583780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(424c5940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(422f8050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(422f8050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42468510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42468510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41d68b60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1643779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41d68b60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(420541d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(420541d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42580090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42580090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b6ebb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1703779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b6ebb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42519b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42519b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4234e460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4234e460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41ceca50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1763780, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41ceca50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42365a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): releaseWL(42365a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(436566b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436566b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42393000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1823779, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  906): Prepared write state in 33ms
,D/PMS     (  906): releaseWL(42393000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-21-01-31-33.bin
,I/ProcessStatsService(  906): Prepared write state in 30ms
,I/ProcessStatsService(  906): Prepared write state in 17ms
,D/PMS     (  906): acquireWL(44062910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/PMS     (  906): releaseWL(44062910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b3e990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b3e990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41f25c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=4393
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
V/AlarmManager(  906): sending alarm PendingIntent{42331428: PendingIntentRecord{42330618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1883779, Int=0
,I/ActivityManager(  906): Killing 4393:com.android.settings:remote/1000 (adj 15): empty for 1807s
I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,I/ActivityManager(  906): Recipient 4393
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(41f25c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4230de58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4230de58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/Process (  906): killProcessQuiet, pid=4151
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  906): Killing 4151:com.android.vending/u0a73 (adj 15): empty for 1800s
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  906): Recipient 4151
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4777): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4777): ====startRecUseTime====
D/htc.customization.log.level( 4777):  is 
W/CustomizationLogLevel( 4777): Level value is invalid, use default level 2
D/CustomizationManager( 4777):  Read ACC file spent 0.124 (s)
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
D/CustomizationManager( 4777):  Read CID file spent 0.181 (s)
D/CustomizationManager( 4777):  All configurations done spent 0.182 (s)
W/HtcNativeFlag( 4777): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4777): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4777): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4777): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4777, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4570
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4570:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/Process (  906): killProcessQuiet, pid=4546
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4530
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=3928
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4546:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  906): Killing 4530:com.google.android.setupwizard/u0a78 (adj 15): empty for 1802s
I/ActivityManager(  906): Killing 3928:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
D/Process (  906): killProcessQuiet, pid=4475
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4475:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1808s
I/ActivityManager(  906): Recipient 4475
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4530
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4570
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3928
D/MediaRouterService(  906): Client com.google.android.music (pid 3928): Died!
W/asset   (  906): Copying FileAsset 0x644ce150 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4546
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  906): Skipping PackageSetting{4219e888 com.example.hello/10356} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/dalvikvm-heap( 4190): Grow heap (frag case) to 15.204MB for 1821008-byte allocation
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
I/acms    ( 1917): Unregistering com.test.thalitest
E/acms    ( 1917): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1580): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1580): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1432): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1324): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1324): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): acquireWL(4341a948): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1432 10028 null
D/PMS     (  906): releaseWL(4341a948): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
D/VoicemailCleanupService( 1292): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/Launcher( 1266): Deferring update until onResume
D/Launcher( 1266): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1324): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PackageBroadcastService( 2264): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1324): Unsupported attribute readOnly
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4791 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/MultiDex( 4791): install
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4791): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  906): Delaying start of: ServiceRecord{4251f750 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4791): loading existing secondary dex files
I/MultiDex( 4791): load found 1 secondary dex files
I/MultiDex( 4791): install done
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4808 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PeopleContactsSync( 2264): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2264, uid=10028, userID:0
D/PMS     (  906): acquireWL(43eed508): PARTIAL_WAKE_LOCK  Icing 0x1 2264 10028 null
I/Icing   ( 2264): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 4791): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  906): releaseWL(43eed508): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4808): install
I/MultiDex( 4808): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4808): loading existing secondary dex files
I/MultiDex( 4808): load found 1 secondary dex files
I/MultiDex( 4808): install done
I/ProviderInstaller( 4808): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1393): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1393): handle notify Blinkfeed plugin client changed
D/Process (  906): killProcessQuiet, pid=4190
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4829 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 4190:com.google.android.apps.plus/u0a160 (adj 15): empty for 1803s
E/SQLiteDatabase( 4791): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4791): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4791): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4791): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4791): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4791): threadid=12: thread exiting with uncaught exception (group=0x41660e30)
E/AndroidRuntime( 4791): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4791): Process: com.google.android.gms.drive, PID: 4791
E/AndroidRuntime( 4791): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4791): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4791): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4791): 	at ctn.run(SourceFile:985)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
D/Process ( 4791): killProcess, pid=4791
D/Process ( 4791): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 4190
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
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
I/ActivityManager(  906): Recipient 4791
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4791) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4829, uid=10073, userID:0
D/Finsky  ( 4829): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4829/10073)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4829/10073)
D/Finsky  ( 4829): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  906): acquireWL(42438178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41d1bf58: PendingIntentRecord{423cc4b8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1660285, Int=0
W/Settings( 4829): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4829): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4829): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4829): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4829): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4829): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4829): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4829): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4829): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4829): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4829): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4829): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4829): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4829): threadid=25: thread exiting with uncaught exception (group=0x41660e30)
E/ActivityManager(  906): App crashed! Process: com.android.vending
E/AndroidRuntime( 4829): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4829): Process: com.android.vending, PID: 4829
E/AndroidRuntime( 4829): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4829): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4829): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4829): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4829): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4829): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4829): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4829): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4829): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4829): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4829, uid=10073, userID:0
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
D/Process ( 4829): killProcess, pid=4829
D/Prism.PackageStateRece_( 1266): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4829): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2912): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4829
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4865 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Process com.android.vending (pid 4829) has died.
I/TrimMemoryManager( 1266): [trimMemory] 5
E/SQLiteLog( 2912): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2912): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5c930e80
W/dalvikvm( 2912): threadid=14: thread exiting with uncaught exception (group=0x41660e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2912): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2912): Process: com.google.android.googlequicksearchbox:search, PID: 2912
E/AndroidRuntime( 2912): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2912): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2912): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2912): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2912): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2912): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2912): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2912): 	at cid.d(PG:186)
E/AndroidRuntime( 2912): 	at clo.g(PG:594)
E/AndroidRuntime( 2912): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2912): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2912): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2912): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2912): 	at clr.tL(PG:827)
E/AndroidRuntime( 2912): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2912): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2912): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2912): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2912): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2912): killProcess, pid=2912
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
D/Process ( 2912): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  906): Recipient 2912
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2912): Died!
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2912) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
W/PackageManager(  906): Unable to load service info ResolveInfo{41b71198 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1266): loadItems() com.htc.launcher.pageview.WidgetManager@41b25d30 +
I/Prism.WidgetManager( 1266): onLoadItems() +
E/SQLiteDatabase( 4865): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4865): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4865): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4865): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4865): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4865): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4865): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4865): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4865): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4865): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4865): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4865): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4865): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4865): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4865): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4865): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4865): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4865): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4865): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4865): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4865): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4865): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4865): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4865): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4865): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4865): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4865): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4865): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4865): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4865): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4865): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4865): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4865): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4865): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4865): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4865): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4865): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4865): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4865): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4865): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4865): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4865): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4865): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4865): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4865): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4865): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4865): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4865): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4865): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4865): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4865): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4865): threadid=11: thread exiting with uncaught exception (group=0x41660e30)
E/AndroidRuntime( 4865): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4865): Process: com.google.android.apps.docs, PID: 4865
E/AndroidRuntime( 4865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4865): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4865): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4865): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4865): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4865): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4881 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4865): killProcess, pid=4865
D/Process ( 4865): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 4865
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4865) has died.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0

```
