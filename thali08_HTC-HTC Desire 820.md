#### Test 56151093914d164_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
,E/cutils-trace( 4408): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4408): ====startRecUseTime====
D/htc.customization.log.level( 4408):  is 
W/CustomizationLogLevel( 4408): Level value is invalid, use default level 2
D/CustomizationManager( 4408):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4408): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4408): Parsing tag category name = system
I/CustomizationCIDLoader( 4408): Parsing tag category name = application
I/CustomizationCIDLoader( 4408): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4408): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4408): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4408): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4408): Parsing tag category name = Settings
D/CustomizationManager( 4408):  Read CID file spent 0.093 (s)
D/CustomizationManager( 4408):  All configurations done spent 0.093 (s)
W/HtcNativeFlag( 4408): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4408): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4408): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4408): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4408
D/PMS     (  905): acquireHCC(41cfa1a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(41b32930): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x69381da8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1105203040
D/PMS     (  905): acquireWL(42044808): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42188570
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4419 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4419): Copying FileAsset 0x5c78f428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1269): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4419): Binding Chromium to main looper Looper (main, tid 1) {41b20ba8}
I/LibraryLoader( 4419): Expected native library version number "",actual native library version number ""
I/chromium( 4419): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4419): Initializing chromium process, renderers=0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425c49b8:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/PMS     (  905): acquireWL(42437f10): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(42f3bdd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(42f3bdd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4419): 1102278760: getState(). Returning 12
I/Adreno-EGL( 4419): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4419): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4419): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4419): Local Branch: 
I/Adreno-EGL( 4419): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4419): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4419):                  aa63bbd948f41d15fc72f585e
W/chromium( 4419): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4419): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4419): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4419): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4419): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4419): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4419): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4419): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4419): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4419): CordovaWebView is running on device made by: HTC
,W/AwContents( 4419): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +260ms
,W/ResourceType( 4419): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4419): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b68718, mServedView=org.apache.cordova.engine.SystemWebView{41b2e380 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4419): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1204): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1204): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1204): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1204): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  905): Disable input method client, pid=1269
I/InputMethodManagerService(  905): Enable input method client, pid=4419
D/PMS     (  905): releaseWL(42044808): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4419): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4419): JniHelper::setJavaVM(0x415f6048), pthread_self() = 1663227424
,D/JX-Cordova( 4419): jxcore cordova android initializing
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 12.000MB for 42652-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 12.087MB for 95956-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 12.158MB for 143930-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 12.272MB for 215890-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 12.448MB for 323830-byte allocation
,D/PMS     (  905): acquireWL(4231c978): PARTIAL_WAKE_LOCK  Icing 0x1 2220 10028 null
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 12.719MB for 485740-byte allocation
,D/PMS     (  905): releaseWL(4231c978): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(44207fc0): PARTIAL_WAKE_LOCK  Icing 0x1 2220 10028 null
,D/PMS     (  905): releaseWL(44207fc0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(426c6ac0): PARTIAL_WAKE_LOCK  Icing 0x1 2220 10028 null
,D/PMS     (  905): releaseWL(426c6ac0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(42379720): PARTIAL_WAKE_LOCK  Icing 0x1 2220 10028 null
,D/PMS     (  905): releaseWL(42379720): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 13.690MB for 1092904-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 14.640MB for 1639352-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 15.884MB for 2459024-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 18.071MB for 3688532-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(41cfa1a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(41b32930): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,W/jxcore-log( 4419): Initializing JXcore engine
,W/jxcore-log( 4419): JXcore engine is ready
,W/jxcore-log( 4419): Starting JXcore engine
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4466 uid=10077 gids={50077}
D/PMS     (  905): acquireWL(4233fb50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
,V/AlarmManager(  905): sending alarm PendingIntent{4236a5b0: PendingIntentRecord{4236a578 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453042968881, Int=60000
,D/PMS     (  905): releaseWL(4233fb50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4466): SMSBackupAgentService started
,D/SMSBackup( 4466): Checking restore status
D/SMSBackup( 4466): Restore complete
,D/SMSBackup( 4466): cancelCheckAlarm
,D/SMSBackup( 4466): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=3194
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3194:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3194
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/jxcore-log( 4419): Platform android
W/jxcore-log( 4419): 
,W/jxcore-log( 4419): Process ARCH arm
W/jxcore-log( 4419): 
,I/jxcore-log( 4419): JXcore Cordova bridge is ready!
I/jxcore-log( 4419): 
,W/jxcore-log( 4419): JXcore engine is started
,I/chromium( 4419): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/PMS     (  905): releaseWL(42437f10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4419): Toggling radios to true
I/jxcore-log( 4419): 
,D/BluetoothAdapter( 4419): enable(): BT is already enabled..!
,D/WifiManager( 4419): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
,W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
D/WifiService(  905): setWifiEnabled: true pid=4419, uid=10189
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
D/WifiService(  905): New client listening to asynchronous messages
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1748
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 3(ms)
D/WifiManager( 4419): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4419): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): TDLS: Tear down peers
I/wpa_supplicant( 1175): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4419): Radios toggled
I/jxcore-log( 4419): 
I/jxcore-log( 4419): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4419): 
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1175): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1175): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1175): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12,
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12,
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb820fbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1175):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error -2 - cmd 12,
I/wpa_supplicant( 1175): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1175): State: DISCONNECTED -> DISCONNECTED
,D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
,I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1175): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
D/Tethering(  905): [isWifi] getHotspotEnabled: false
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  905): acquireWL(42606798): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  905): [RunningState] Stop DHCP
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): Fast associate: Old scan results
I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20013 mDataStallAlarmIntent=PendingIntent{424043d0: PendingIntentRecord{4250b3c8 android broadcastIntent}}
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): Enter handleNetworkDisconnect
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1845/10178)
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/WISPrService( 3830): >>>>>WISPrService start isConnected = false<<<<<
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905):    returned true
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService(  905): New client listening to asynchronous messages
D/WISPrService( 3830): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/PMS     (  905): acquireWL(42422df0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/libc    (  364): [NET] entry_id:6   entry:0xb7efbcf0  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb7f00258  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7f00358  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7efbc20  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7f04c28  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7f04f70  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb7efbaf8  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb7f04d38  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7f00468  removed 
D/libc    (  364): [NET] entry_id:10   entry:0xb7efb9a0  removed 
D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): Exit handleNetworkDisconnect
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  905): acquireWL(43e1e108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(42caf508): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1364/10028)
D/WISPrService( 3830): >>>>>WISPrService start isConnected = false<<<<<
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WISPrService( 3830): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/PMS     (  905): releaseWL(43e1e108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1845/10178)
,D/WifiNative-wlan0(  905): doBoolean: SCAN
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1175): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
,D/PMS     (  905): releaseWL(42422df0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/WifiNative-wlan0(  905):    returned false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  905): releaseWL(42caf508): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43af9998): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1845/10178)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1888/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4308/10100)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3901/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1434/10028)
,I/NetworkMonitor( 3901): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4308/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2473/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4488 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4488): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4488): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4488): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4488): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4488): Preparing secondary program dexes.
V/DexLibLoader( 4488): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4488): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4488): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4488): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4488): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4488): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4488): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4488): Dex already copied
D/OdexVerifier( 4488): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4488): Creating class loader
,V/DexLibLoader( 4488): Finished creating class loader
V/DexLibLoader( 4488): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4488): Dex already copied
D/OdexVerifier( 4488): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4488): Creating class loader,
V/DexLibLoader( 4488): Finished creating class loader,
V/DexLibLoader( 4488): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4488): Dex already copied
D/OdexVerifier( 4488): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4488): Creating class loader,
V/DexLibLoader( 4488): Finished creating class loader,
V/DexLibLoader( 4488): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4488): Dex already copied
D/OdexVerifier( 4488): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4488): Creating class loader,
V/DexLibLoader( 4488): Finished creating class loader
,V/DexLibLoader( 4488): Verifying classes from secondary dexes.,
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/DexLibLoader( 4488): DexLibLoader.ensureDexLoaded took 18 ms,
D/PMS     (  905): releaseWL(43af9998): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/dalvikvm( 4488): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4488): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4488): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4488): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4488): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4488): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4488): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1175): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1175): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1175): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1175): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 3
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 1
I/wpa_supplicant( 1175): wpa_s->is_screen_on 1
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): selected network = 2
D/wpa_supplicant( 1175): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb82114e8  current_ssid=0x0
D/wpa_supplicant( 1175): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1175): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1175): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1175): check if in concurrent case
I/wpa_supplicant( 1175): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,W/dalvikvm( 4488): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1780,
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1175): RSN: PMKSA cache search - network_ctx=0xb82114e8 try_opportunistic=0
D/wpa_supplicant( 1175): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1175): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1175): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1175): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1175): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1175): nl80211: Unsubscribe mgmt frames handle 0xb8210718 (mode change)
D/wpa_supplicant( 1175): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8210718
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8210718,
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8210718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8210718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8210718
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8210718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8210718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8210718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8210718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8210718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8210718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1175):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1175):   * freq=2412
D/wpa_supplicant( 1175):   * Auth Type 0
D/wpa_supplicant( 1175):   * WPA Versions 0x2
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1175): nl80211: Connect request send successfully
,D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1175): reply (489) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-48
I/wpa_supplicant( 1175): tsf=0000000022052182,
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48,
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000107611202
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000107611206
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-84
I/wpa_supplicant( 1175): tsf=0000000107611210
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): == begin of scan result ==
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 22052182, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 107611202, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 107611206, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2427, timestamp: 107611210, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/dalvikvm( 4488): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1175): nl80211: Connect event
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1175): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1175): Add randomness: count=11 entropy=4
I/wpa_supplicant( 1175): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1175): TDLS: Remove peers on association
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1175): EAPOL: enable timer tick
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1175): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1175): Get randomness: len=32 entropy=5
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/Tethering(  905): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1175): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb82109f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1175):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1175): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f70b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1175):    broadcast key
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1175): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1175): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1175): setConcurrentAPChannel: Set wifi.hotspot.channel to 1,
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1175): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=6,
I/wpa_supplicant( 1175): set send_ind_to_ndc = 0
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1175): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Authorized,
D/wpa_supplicant( 1175): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1175): EAPOL authentication completed successfully
I/wpa_supplicant( 1175): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,E/FbInjectorInitializer( 4488): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3830): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3830): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 1
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(42aac4a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
,D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4249e578 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4249e578 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4488): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4488): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4488): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=4246
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4246:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  905): acquireWL(425cb270): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2220 10028 null
I/ActivityManager(  905): Recipient 4246
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): acquireWL(4319c730): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2220 10028 null
,D/PMS     (  905): releaseWL(425cb270): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2220/10028)
,D/PMS     (  905): releaseWL(4319c730): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1364): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2220/10028)
,D/AutoSetting( 1402): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4517 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,D/AutoSetting( 1402): Util - no network available!
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,D/AutoSetting( 1402): service - onCreate()
,D/AutoSetting( 1402): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  905): request 425c6208 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1402): service - mHandler: cancel location update
,D/AutoSetting( 1402): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4488): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4488): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4488): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4517): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4517): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4517): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4517): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4533 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4517/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4517/10078)
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4517/10078)
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/Process (  905): killProcessQuiet, pid=3884
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4550 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 3884:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 9.965MB for 84664-byte allocation
E/dalvikvm( 4488): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4488): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4550): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 9.981MB for 28144-byte allocation
E/dalvikvm( 4488): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4488): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4488): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4488): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4488): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4488): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4488): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4488): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4488): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4488): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4488): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4488): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4488): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/dalvikvm( 4488): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4488): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4488): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3884
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 10.025MB for 39954-byte allocation
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 10.100MB for 79892-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4550/10151)
,V/WebViewChromiumFactoryProvider( 4550): Binding Chromium to main looper Looper (main, tid 1) {41b26368}
,I/LibraryLoader( 4550): Expected native library version number "",actual native library version number ""
,I/chromium( 4550): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4550): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(42f5d330): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  905): acquireWL(431b3c50): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4550): BLUETOOTH permission is missing!
D/PMS     (  905): releaseWL(42f5d330): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4550): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4550): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4550): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4550): Local Branch: 
I/Adreno-EGL( 4550): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4550): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4550):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4550): Starting up...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4550/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4550/10151)
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 10.288MB for 75760-byte allocation
,D/Process (  905): killProcessQuiet, pid=4004
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4160/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4160/10160)
I/ActivityManager(  905): Killing 4004:com.google.android.gm/u0a107 (adj 15): empty #17
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1845/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1845/10178)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44242eb0 u0 ReceiverList{44242d90 4488 com.facebook.katana/10026/u0 remote:4421fa50}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44242eb0 u0 ReceiverList{44242d90 4488 com.facebook.katana/10026/u0 remote:4421fa50}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{435d79e0 u0 ReceiverList{435d7980 4488 com.facebook.katana/10026/u0 remote:435bcf20}}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
,D/PMS     (  905): acquireWL(42f3d4b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
,D/PMS     (  905): releaseWL(42f3d4b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1434): Unknown pending intent to remove.
D/PMS     (  905): acquireWL(4381d9e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
D/PMS     (  905): releaseWL(4381d9e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  905): Recipient 4004
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1175): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1175): EAPOL: disable timer tick
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,I/jxcore-log( 4419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4419): 
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,I/jxcore-log( 4419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4419): 
,I/jxcore-log( 4419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4419): 
,I/jxcore-log( 4419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4419): 
,I/jxcore-log( 4419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4419): 
,I/jxcore-log( 4419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4419): 
,I/jxcore-log( 4419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4419): 
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1175): Change stage from stage0 to stage3
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
D/PMS     (  905): releaseWL(42aac4a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1175): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20015 delay=15s
,D/WifiWatchdogStateMachine(  905): WAN detection
,D/WISPrService( 3830): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1845/10178)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
,D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@4244e268
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(43696948): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4517/10078)
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  905): acquireWL(43cc29f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2220 10028 null
,D/PMS     (  905): acquireWL(43dffb88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2220 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  905): releaseWL(43cc29f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2220/10028)
,I/CheckinService( 2220): Preparing to send checkin request
,I/EventLogService( 2220): Accumulating logs since 1453042919471
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/GoogleHttpClient( 2220): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2220): Using GMS GoogleHttpClient
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(43696948): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2220/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2220/10028)
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2220): awaiting user notification for token
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ba75c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 6 3 12
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4625 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4625): install
,I/MultiDex( 4625): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4625): loading existing secondary dex files
,I/MultiDex( 4625): load found 1 secondary dex files
,I/MultiDex( 4625): install done
,I/ProviderInstaller( 4625): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/jxcore-log( 4419): Test app app.js loaded
I/jxcore-log( 4419): 
,I/Choreographer( 4419): Skipped 278 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4419): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Adreno-EGL( 4625): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4625): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4625): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4625): Local Branch: 
I/Adreno-EGL( 4625): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4625): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4625):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4625): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4625): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4625): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4625): Local Branch: 
I/Adreno-EGL( 4625): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4625): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4625):                  aa63bbd948f41d15fc72f585e
,I/SensorManager(  905): mEventCount = 900
,D/WIFI_ICON( 1114): WifiActivity: 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  905): releaseWL(42606798): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3923/10051)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1434/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1845/10178)
D/PMS     (  905): acquireWL(434c5d80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(434c5d80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/CaptivePortalTracker(  905): NoActiveNetworkState
I/acms    ( 1888): Checking Certificates
I/acms    ( 1888): Checking Developer Certificates
I/acms    ( 1888): Checking Application Certificates
I/acms    ( 1888): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1888): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1888): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/acms    ( 1888): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/acms    ( 1888): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1888): Updating next query delay: 75600000
I/mlserverapp( 1888): MirrorLink is never connected, don't setup ACMS programed checks
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
I/mlserverapp( 1888): cancelACMSProgrammedChecks
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1888/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4517/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4308/10100)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3901/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42fa6d70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/NetworkMonitor( 3901): type=WIFI subType= reason=null isConnected=true
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1434/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4308/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  905): acquireWL(423a4d18): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4646 uid=10106 gids={50106, 3003, 5012}
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2473/10021)
D/PMS     (  905): releaseWL(42fa6d70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
D/PMS     (  905): acquireWL(41e982e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2220 10028 null
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(41e982e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1364): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  905): acquireWL(42e8bfe8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1364 10028 null
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1364): [NET] getaddrinfo-,err=8
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1364): [NET] getaddrinfo-, 1
,D/libc    ( 1364): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1a60 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2220/10028)
,D/AutoSetting( 1402): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4517): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4517): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4550/10151)
,D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1402): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1402): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1402): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1402): service - handleMessage() setting current location null
,D/AutoSetting( 1402): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1402): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/Adreno-EGL( 4625): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4625): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4625): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4625): Local Branch: 
I/Adreno-EGL( 4625): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4625): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4625):                  aa63bbd948f41d15fc72f585e
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4160/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4160/10160)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1845/10178)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 230
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1364): [NET] getaddrinfo_proxy-, success
,I/NewsWeather( 4646): LocationClient connecting
,D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1364): [NET] getaddrinfo-,err=8
,I/NewsWeather( 4646): NewsAccounts: 2, AllSystemAccounts 1.
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  905): acquireWL(42539318): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  905): releaseWL(42539318): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/dalvikvm( 4646): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4646): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4646): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4646): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4646): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [5][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-60 , oldRssi= -200
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
,W/fb4a(:<default>):UserScope( 4488): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4488): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/Settings( 4625): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,I/ProviderInstaller( 4646): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42523998): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(42523998): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4646): Last usage 0, idle 1453042975s, sync interval 2592000s
,I/NewsWeather( 4646): setPeriodicSync in seconds 2592000
,D/GCM     ( 1364): Connected
D/PMS     (  905): acquireWL(42541680): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
,I/NewsWeather( 4646): onConnected null
,W/GCoreFlp( 1434): No location to return for getLastLocation()
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4625/10028)
D/PMS     (  905): releaseWL(42e8bfe8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/PMS     (  905): acquireWL(42385b48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/PMS     (  905): acquireWL(43823520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
,I/NewsWeather( 4646): LocationClient onConnected: location null
D/PMS     (  905): releaseWL(42385b48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  905): releaseWL(42541680): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(42619218): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/PMS     (  905): releaseWL(43823520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4646): Skip sync for lookup editions
,I/NewsWeather( 4646): syncNewsAppData traffic type BACKGROUND_POLL
,D/GCM     ( 1364): Message class mpf
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
,I/CheckinTask( 2220): Sending checkin request (9012 bytes)
D/libc    ( 2220): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2220): [NET] getaddrinfo-,err=8
D/libc    ( 2220): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2220): [NET] getaddrinfo-, 1
,D/libc    ( 2220): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ae83 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  905): releaseWL(42619218): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(42379960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,I/NewsWeather( 4646): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
D/PMS     (  905): releaseWL(42379960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 279
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2220): [NET] getaddrinfo_proxy-, success
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4646): Unrecoverable authentication exception
E/NewsWeather( 4646): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4646): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4646): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4646): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41c68320 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 2 6 3 12
,D/libc    ( 4646): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4646): [NET] getaddrinfo-,err=8
D/libc    ( 4646): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4646): [NET] getaddrinfo-, 1
,D/libc    ( 4646): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =779c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,E/fb4a(:<default>):LocalFbBroadcastManager( 4488): Called registerBroadcastReceiver twice.
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=70
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4646): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2220): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2220): [NET] getaddrinfo-,err=8
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4217a360
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4217a360, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42114340
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@41fd6dc0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  905): mWirelessDisplayManager is null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
,D/libc    ( 4646): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4646): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(437bb2a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  905): releaseWL(437bb2a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4646): Failed to syncNewsAppData
,E/NewsWeather( 4646): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(433d77e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 68134, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(423a4d18): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/Process (  905): killProcessQuiet, pid=4278
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/ActivityManager(  905): Killing 4278:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/PMS     (  905): releaseWL(433d77e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1434/10028)
D/PMS     (  905): acquireWL(438bcb98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(438bcb98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=10 [28][3][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  905): Recipient 4278
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 370ms
D/PMS     (  905): nativeSetInteractive:false
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1252): ScreenObserver: OFF
,D/NfcService( 1252): applyRouting - 0
D/NfcService( 1252): applyRouting -2
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@44251940)
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
D/PMS     (  905): releaseWL(431b3c50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
D/PMS     (  905): acquireWL(442b6610): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
D/PMN     (  905): wakingUp
D/PMS     (  905): releaseWL(442b6610): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputMethodManagerService(  905): Disable input method client, pid=4419
W/ResourceType( 4419): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4419): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b2e380 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/PMS     (  905): acquireWL(4366cf38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(4366cf38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  905): No lock screen! windowToken=null
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMN     (  905): onScreenOn
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,D/MtpService( 2473): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1252): applyRouting - 0
,D/MtpService( 2473): [MTP][onReceive]-
I/HtcPowerSaver(  905): << updateStatus
,D/PMS     (  905): acquireWL(431e1370): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
D/NfcService( 1252): applyRouting -2
,D/AutoSetting( 1402): receiver - intent: android.intent.action.USER_PRESENT
D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  905): releaseWL(431e1370): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  905): acquireWL(42ca7b68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20016 delay=15s
,I/ClockThread( 1114): stop update clock
D/TetherSettings( 3830): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3830): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3830): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3830): Cust_ConnectToPC   : spcsc>false
D/        ( 3830): Cust_ConnectToPC   : IPT>true
D/        ( 3830): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3830): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3830): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3830): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3830): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  905): releaseWL(42ca7b68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I/PSReceiver( 3830): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [3][0][0]
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): SET_SCREEN_ON:On
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1175): BG scan when screen On
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): Match BG scan, scan!
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =2
,I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
D/WifiNative-wlan0(  905):    returned true
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96,
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
I/SmartNS_PSService( 3830): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3830): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3830):  defaultType:0
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2220/10028)
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2220/10028)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
D/NetworkPolicy(  905): updateScreenOn: false
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4689 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(4234ab48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1810): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1810): onScreenOn: 1453042976343
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1810): onScreenOn: 1453042976343
D/PMS     (  905): releaseWL(4234ab48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42114340
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42114340, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@41fd6dc0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
,D/PMS     (  905): acquireWL(44183b58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,W/ContextImpl( 4689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20016 mDataStallAlarmIntent=PendingIntent{424c23d0: PendingIntentRecord{4250b3c8 android broadcastIntent}}
,D/SmartSyncUtils( 4689): isEpsOn(), nState = 0
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/PMS     (  905): releaseWL(44183b58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
D/PMS     (  905): acquireWL(426a23c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): acquireWL(4338f9e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4689 1000 null
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,D/SmartSyncUtils( 4689): getMobilePolicyEnabled, result = true
,D/Process (  905): killProcessQuiet, pid=4308
D/PMS     (  905): releaseWL(4338f9e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  905): Killing 4308:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2220): awaiting user notification for token
,I/CheckinTask( 2220): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2220): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2220/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2220/10028)
,D/PMS     (  905): releaseWL(43dffb88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2220): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bfffe0 that was originally bound here
E/ActivityThread( 2220): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bfffe0 that was originally bound here
E/ActivityThread( 2220): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2220): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2220): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2220): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2220): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2220): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2220): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2220): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2220): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2220): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2220): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2220): 	at bks.a(SourceFile:298)
E/ActivityThread( 2220): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2220): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2220): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2220): 	at java.lang.Thread.run(Thread.java:864)
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4308
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): SET_SCREEN_ON:Off
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6,
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6,
,I/wpa_supplicant( 1175): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1175): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
V/SRS_Proc(  371): ParamSet string: screen_state=off
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9904 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41c735a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 2 11 3 12
,D/SmartSyncUtils( 4689): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4689): getMobilePolicyEnabled, result = true
,W/ContextImpl( 4689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4689): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,D/NetworkPolicy(  905): updateScreenOn: false
D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
D/ContactMessageStore( 1241): Background delete complete
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41fd6dc0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
,W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41fd6dc0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41fd6dc0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41fd6dc0
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42128b40 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42128b40 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  905): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  905): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  905): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  905): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  905): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  905): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  905): 	at dalvik.system.NativeStart.main(Native Method)
,I/GCM     ( 1364): GCM config loaded
,D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  905): acquireWL(44465288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
,D/PMS     (  905): releaseWL(44465288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1810): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1810): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1810): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1810): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1810): onScreenOff
,D/AutoSetting( 1402): service - mHandler: cancel location update
,D/AutoSetting( 1402): service -           changes count: 0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(426a23c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/GAV2    ( 4550): Thread[GAThread,5,main]: No campaign data found.
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-86
D/wpa_supplicant( 1175): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=12 entropy=0
D/wpa_supplicant( 1175): Add randomness: count=13 entropy=1
D/wpa_supplicant( 1175): Add randomness: count=14 entropy=2
D/wpa_supplicant( 1175): Add randomness: count=15 entropy=3
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-6,0
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-86
D/wpa_supplicant( 1175): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=16 entropy=4
D/wpa_supplicant( 1175): Add randomness: count=17 entropy=5
D/wpa_supplicant( 1175): Add randomness: count=18 entropy=6
D/wpa_supplicant( 1175): Add randomness: count=19 entropy=7
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
,I/wpa_supplicant( 1175): No suitable network found
,W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: DISCONNECTED -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1175): reply (489) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-48
I/wpa_supplicant( 1175): tsf=0000000113718610
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000113718637
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000113718647
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
,I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-86
I/wpa_supplicant( 1175): tsf=0000000113718676
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ####
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 113718610, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 113718637, distance: ?(cm), distanceSd: ?(cm)
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4250da80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@4250da80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@4250da80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 113718647, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2427, timestamp: 113718676, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 4 to mScanResults
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  905):  + computeScore(NG700): 1,
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1515): service - handleMessage() stop self
,D/AutoSetting( 1515): service - onDestroy() END
,D/AutoSetting( 1515): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4331
,I/ActivityManager(  905): Killing 4331:com.htc.backup/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4331
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(435cb5f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42274050: PendingIntentRecord{420d5800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=115480, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(435cb5f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/GAV4    ( 4646): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=4349
,I/ActivityManager(  905): Killing 4349:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4349
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 10.993MB for 37000-byte allocation
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 11.022MB for 55496-byte allocation
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 11.039MB for 54604-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 11.114MB for 82928-byte allocation
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 11.121MB for 55844-byte allocation
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 11.161MB for 72430-byte allocation
,D/libc    ( 4488): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4488): [NET] getaddrinfo-,err=8
D/libc    ( 4488): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4488): [NET] getaddrinfo-, 1
,D/libc    ( 4488): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a3b0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 39
D/libc    (  364): [NET]res_nsend:resplen=93
D/libc    (  364): [NET]res_queryN: exit 3, ancount=3
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4488): [NET] getaddrinfo_proxy-, success
I/global  ( 4488): call createSocket() return a new socket.
D/libc    ( 4488): [NET] getaddrinfo+,hn 13(0x3137392e36302e),sn(),family 0,flags 4
,D/libc    ( 4488): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4488): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4488): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(433964d0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4488 10026 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10026)
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4488): I/O error closing connection
I/global  ( 4488): java.net.SocketException: Socket is closed
I/global  ( 4488): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4488): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4488): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4488): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4488): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4488): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4488): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4488): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4488): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4488): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4488): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4488): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4488): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4488): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4488): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4488): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4488): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4488): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4488): Removing a connection that never existed!
D/PMS     (  905): releaseWL(433964d0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43c924b8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-89
D/wpa_supplicant( 1175): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=20 entropy=8
D/wpa_supplicant( 1175): Add randomness: count=21 entropy=9
D/wpa_supplicant( 1175): Add randomness: count=22 entropy=10
D/wpa_supplicant( 1175): Add randomness: count=23 entropy=11
D/wpa_supplicant( 1175): Add randomness: count=24 entropy=12
D/wpa_supplicant( 1175): Add randomness: count=25 entropy=13
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
,I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 5: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (6 BSSes)
,D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
,I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-89
D/wpa_supplicant( 1175): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=26 entropy=14
,D/wpa_supplicant( 1175): Add randomness: count=27 entropy=15
D/wpa_supplicant( 1175): Add randomness: count=28 entropy=16
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1175): Add randomness: count=29 entropy=17
D/wpa_supplicant( 1175): Add randomness: count=30 entropy=18
,D/wpa_supplicant( 1175): Add randomness: count=31 entropy=19
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
,W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1175): reply (763) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-48
I/wpa_supplicant( 1175): tsf=0000000131034171
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
,I/wpa_supplicant( 1175): tsf=0000000131034197
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000131034207
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-85
,I/wpa_supplicant( 1175): tsf=0000000131034217
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=4
I/wpa_supplicant( 1175): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-87
I/wpa_supplicant( 1175): tsf=0000000131034226
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5,
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-89
I/wpa_supplicant( 1175): tsf=0000000131034237
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 131034171, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 131034197, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 131034207, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2427, timestamp: 131034217, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 131034226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2462, timestamp: 131034237, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  76, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  76, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(423a9388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d1f120: PendingIntentRecord{424c0b00 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=131380, Int=0
,D/PMS     (  905): acquireWL(4236a5c0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(423a9388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(420e99d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4236a5c0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(420e99d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(4245c4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4245c4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425c4438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425c4438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1402): service - mHandler: update timezone
,D/AutoSetting( 1515): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1515): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1515): service - onCreate()
,D/AutoSetting( 1515): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1515): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1605): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1515): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1515): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1515): service - mHandler: update timezone
,D/AutoSetting( 1515): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1515): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1515): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1515): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ec7c78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 3 5 3 11
,D/AutoSetting( 1402): service - handleMessage() stop self
,D/AutoSetting( 1402): service - onDestroy() END
,D/AutoSetting( 1402): service - handleMessage() quit looper
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/Process (  905): killProcessQuiet, pid=3923
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3923:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3923
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-89
D/wpa_supplicant( 1175): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=32 entropy=20
D/wpa_supplicant( 1175): Add randomness: count=33 entropy=21
D/wpa_supplicant( 1175): Add randomness: count=34 entropy=22
D/wpa_supplicant( 1175): Add randomness: count=35 entropy=23
D/wpa_supplicant( 1175): Add randomness: count=36 entropy=24
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Re,ceived scan results (5 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-89
D/wpa_supplicant( 1175): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=37 entropy=25
D/wpa_supplicant( 1175): Add randomness: count=38 entropy=26
D/wpa_supplicant( 1175): Add randomness: count=39 entropy=27
D/wpa_supplicant( 1175): Add randomness: count=40 entropy=28
D/wpa_supplicant( 1175): Add randomness: count=41 entropy=29
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1175): reply (763) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000148353224,
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000131034197
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
,I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000148353257
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-85
I/wpa_supplicant( 1175): tsf=0000000148353267
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=4
I/wpa_supplicant( 1175): bssid=dc:4a:3e:0f:c2:f1,
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-87
I/wpa_supplicant( 1175): tsf=0000000131034226
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-89
,I/wpa_supplicant( 1175): tsf=0000000148353276
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 148353224, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 131034197, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 148353257, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2427, timestamp: 148353267, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 131034226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2462, timestamp: 148353276, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  76, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  76, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4372d538 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  905): acquireWL(42555850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
V/AlarmManager(  905): sending alarm PendingIntent{423c0258: PendingIntentRecord{423bdce8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141481, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{441e9728: PendingIntentRecord{423ad2d8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142614, Int=0
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(4238ae40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
V/AlarmManager(  905): sending alarm PendingIntent{41d1f120: PendingIntentRecord{424c0b00 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=161403, Int=0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  905): acquireWL(43ccb940): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): acquireWL(43736ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  905): releaseWL(42555850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  905): releaseWL(43736ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+,
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5e92 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42473ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=9 [63][6][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/PMS     (  905): acquireWL(43cf84e8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
D/PMS     (  905): releaseWL(43ccb940): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  905): releaseWL(42473ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(423fcce0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(423fcce0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4646): Last usage 0, idle 1453043026s, sync interval 2592000s
I/NewsWeather( 4646): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4646): Skip sync for lookup editions
,I/NewsWeather( 4646): syncNewsAppData traffic type BACKGROUND_POLL
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,I/NewsWeather( 4646): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4646): Unrecoverable authentication exception
E/NewsWeather( 4646): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4646): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4646): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4646): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ba75c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 11 6 12
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): acquireWL(426daac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,E/NewsWeather( 4646): Failed to syncNewsAppData
,E/NewsWeather( 4646): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): releaseWL(426daac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(425bc630): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 111396, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(43cf84e8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1434/10028)
D/PMS     (  905): releaseWL(425bc630): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4370c9b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4370c9b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-83
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-89
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
D/wpa_supplicant( 1175): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=42 entropy=30
D/wpa_supplicant( 1175): Add randomness: count=43 entropy=31
D/wpa_supplicant( 1175): Add randomness: count=44 entropy=32
D/wpa_supplicant( 1175): Add randomness: count=45 entropy=33
D/wpa_supplicant( 1175): Add randomness: count=46 entropy=34
D/wpa_supplicant( 1175): Add randomness: count=47 entropy=35
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable ,network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-83
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-89
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
D/wpa_supplicant( 1175): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=48 entropy=36
D/wpa_supplicant( 1175): Add randomness: count=49 entropy=37
D/wpa_supplicant( 1175): Add randomness: count=50 entropy=38
D/wpa_supplicant( 1175): Add randomness: count=51 entropy=39
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1175): Add randomness: count=52 entropy=40
D/wpa_supplicant( 1175): Add randomness: count=53 entropy=41
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
I/wpa,_supplicant( 1175): reply (761) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000165582491
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000131034197
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-59
I/wpa_supplicant( 1175): tsf=0000000165582528
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-83
I/wpa_supplicant( 1175): tsf=0000000165582538
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-89
I/wpa_supplicant( 1175): tsf=0000000165582558
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-89
I/wpa_supplicant( 1175): tsf=0000000165582547
I/wpa_supplicant( 1175): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=UPC Wi-Free
I/wpa_supplicant( 1175): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 165582491, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 131034197, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 165582528, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2427, timestamp: 165582538, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2462, timestamp: 165582558, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 165582547, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  76, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(4238ae40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1515): service - handleMessage() stop self
,D/AutoSetting( 1515): service - onDestroy() END
,D/AutoSetting( 1515): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4365
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4365:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4365
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42f64698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42274050: PendingIntentRecord{420d5800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=175480, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42f64698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1175): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=54 entropy=42
D/wpa_supplicant( 1175): Add randomness: count=55 entropy=43
D/wpa_supplicant( 1175): Add randomness: count=56 entropy=44
D/wpa_supplicant( 1175): Add randomness: count=57 entropy=45
D/wpa_supplicant( 1175): Add randomness: count=58 entropy=46
D/wpa_supplicant( 1175): Add randomness: count=59 entropy=47
D/wpa_supplicant( 1175): Add randomness: count=60 entropy=48
D/wpa_supplicant( 1175): Add randomness: count=61 entropy=49
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
,I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 5: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 7: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1175): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=62 entropy=50
D/wpa_supplicant( 1175): Add randomness: count=63 entropy=51
D/wpa_supplicant( 1175): Add randomness: count=64 entropy=52
D/wpa_supplicant( 1175): Add randomness: count=65 entropy=53
D/wpa_supplicant( 1175): Add randomness: count=66 entropy=54
D/wpa_supplicant( 1175): Add randomness: count=67 entropy=55
D/wpa_supplicant( 1175): Add randomness: count=68 entropy=56
D/wpa_supplicant( 1175): Add randomness: count=69 entropy=57
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1175): reply (1053) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000165582491
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
,I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000131034197
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-59
I/wpa_supplicant( 1175): tsf=0000000183024094
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3,
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-82
I/wpa_supplicant( 1175): tsf=0000000183024104
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000183024135
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000183024114
I/wpa_supplicant( 1175): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1175): ssid=UPC Wi-Free
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=7
I/wpa_supplicant( 1175): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-87
I/wpa_supplicant( 1175): tsf=0000000183024123
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=8
I/wpa_supplicant( 1175): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-91
I/wpa_supplicant( 1175): tsf=0000000183024145
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+T
,D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 165582491, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 131034197, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 183024094, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 183024104, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 183024135, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 183024114, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 183024123, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 183024145, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 8 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  68, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (8) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/PMS     (  905): acquireWL(441cc0f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d1f120: PendingIntentRecord{424c0b00 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=191499, Int=0
,D/PMS     (  905): acquireWL(42633538): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(441cc0f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(44219230): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42633538): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(44219230): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(43386c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43386c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-83
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1175): [NULL] 76:04:2b:1b:09:43 freq=2437 level=-90
D/wpa_supplicant( 1175): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=70 entropy=58
D/wpa_supplicant( 1175): Add randomness: count=71 entropy=59
D/wpa_supplicant( 1175): Add randomness: count=72 entropy=60
D/wpa_supplicant( 1175): Add randomness: count=73 entropy=61
D/wpa_supplicant( 1175): Add randomness: count=74 entropy=62
D/wpa_supplicant( 1175): Add randomness: count=75 entropy=63
D/wpa_supplicant( 1175): Add randomness: count=76 entropy=64
D/wpa_supplicant( 1175): Add randomness: count=77 entropy=65
D/wpa_supplicant( 1175): Add randomness: count=78 entropy=66
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP 76:04:2b:1b:09:43 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 6: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 7: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 8: 76:04:2b:1b:09:43 ssid='Lenovo TAB 2 A7-30H' wpa_ie_len=0 rsn_ie_len=0 wapi_ie_len=0 caps=0x421
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-83
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1175): [NULL] 76:04:2b:1b:09:43 freq=2437 level=-90
D/wpa_supplicant( 1175): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=79 entropy=67
D/wpa_supplicant( 1175): Add randomness: count=80 entropy=68
D/wpa_supplicant( 1175): Add randomness: count=81 entropy=69
D/wpa_supplicant( 1175): Add randomness: count=82 entropy=70
D/wpa_supplicant( 1175): Add randomness: count=83 entropy=71
D/wpa_supplicant( 1175): Add randomness: count=84 entropy=72
D/wpa_supplicant( 1175): Add randomness: count=85 entropy=73
D/wpa_supplicant( 1175): Add randomness: count=86 entropy=74
D/wpa_supplicant( 1175): Add randomness: count=87 entropy=75
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: AP 76:04:2b:1b:09:43 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1175): reply (1170) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
,I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000200454106
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000131034197
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-59
I/wpa_supplicant( 1175): tsf=0000000200454144
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-83
I/wpa_supplicant( 1175): tsf=0000000200454154
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
,I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000200454196
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000200454164
I/wpa_supplicant( 1175): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=UPC Wi-Free
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=7
I/wpa_supplicant( 1175): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000200454174
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=8
I/wpa_supplicant( 1175): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-91
I/wpa_supplicant( 1175): tsf=0000000200454207
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+T
,D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 200454106, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 131034197, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 200454144, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2427, timestamp: 200454154, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 200454196, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 200454164, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 200454174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 200454207, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 8: scan result = SSID: Lenovo TAB 2 A7-30H, BSSID: 76:04:2b:1b:09:43, capabilities: [WPS][ESS], level: -90, frequency: 2437, timestamp: 200454184, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 9 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0,
V/ScoreHelper(  905):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:              Lenovo TAB 2 A7-30H [76:04:2b:1b:09:43], Rssi:  0 [-90], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (9) end of scan result ==
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 76:04:2b:1b:09:43 freq=2437 level=-90
D/wpa_supplicant( 1175): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=88 entropy=76
D/wpa_supplicant( 1175): Add randomness: count=89 entropy=77
D/wpa_supplicant( 1175): Add randomness: count=90 entropy=78
D/wpa_supplicant( 1175): Add randomness: count=91 entropy=79
D/wpa_supplicant( 1175): Add randomness: count=92 entropy=80
D/wpa_supplicant( 1175): Add randomness: count=93 entropy=81
D/wpa_supplicant( 1175): Add randomness: count=94 entropy=82
D/wpa_supplicant( 1175): Add randomness: count=95 entropy=83
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59,
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411,
D/wpa_supplicant( 1175): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 6: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 7: 76:04:2b:1b:09:43 ssid='Lenovo TAB 2 A7-30H' wpa_ie_len=0 rsn_ie_len=0 wapi_ie_len=0 caps=0x421
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
,I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 76:04:2b:1b:09:43 freq=2437 level=-90
D/wpa_supplicant( 1175): BSS: last_scan_res_used=8/32 last_scan_full=0
,D/wpa_supplicant( 1175): Add randomness: count=96 entropy=84
D/wpa_supplicant( 1175): Add randomness: count=97 entropy=85
D/wpa_supplicant( 1175): Add randomness: count=98 entropy=86
D/wpa_supplicant( 1175): Add randomness: count=99 entropy=87
D/wpa_supplicant( 1175): Add randomness: count=100 entropy=88
D/wpa_supplicant( 1175): Add randomness: count=101 entropy=89
D/wpa_supplicant( 1175): Add randomness: count=102 entropy=90
D/wpa_supplicant( 1175): Add randomness: count=103 entropy=91
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1175): reply (1170) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000217843907
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000131034197
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-59,
I/wpa_supplicant( 1175): tsf=0000000217843945
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-85
I/wpa_supplicant( 1175): tsf=0000000217843956
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000217843997
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000217843977
I/wpa_supplicant( 1175): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=UPC Wi-Free
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=7
I/wpa_supplicant( 1175): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000200454174
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=8
,I/wpa_supplicant( 1175): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000217843987
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+T
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 217843907, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 131034197, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 217843945, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2427, timestamp: 217843956, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 217843997, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 217843977, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 200454174, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  905): 7: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 217843987, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 8: scan result = SSID: Lenovo TAB 2 A7-30H, BSSID: 76:04:2b:1b:09:43, capabilities: [WPS][ESS], level: -90, frequency: 2437, timestamp: 217843966, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 9 to mScanResults,
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  70, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:              Lenovo TAB 2 A7-30H [76:04:2b:1b:09:43], Rssi:  0 [-90], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (9) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43d57378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d1f120: PendingIntentRecord{424c0b00 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=224293, Int=0
,D/PMS     (  905): acquireWL(43258730): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): releaseWL(43d57378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42e66070): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=10 [55][6][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(42aaca58): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(43258730): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(42e66070): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(433a4068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/NewsWeather( 4646): Last usage 0, idle 1453043088s, sync interval 2592000s
,I/NewsWeather( 4646): setPeriodicSync in seconds 2592000
D/PMS     (  905): releaseWL(433a4068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4646): Skip sync for lookup editions
,I/NewsWeather( 4646): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4646): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4646): Unrecoverable authentication exception
E/NewsWeather( 4646): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4646): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4646): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4646): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4646): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41b69ee8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 10 3 12
,D/PMS     (  905): acquireWL(43b4fea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,E/NewsWeather( 4646): Failed to syncNewsAppData
,E/NewsWeather( 4646): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): releaseWL(43b4fea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43e6b450): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42aaca58): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 161934, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1434/10028)
D/PMS     (  905): releaseWL(43e6b450): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(433bd9b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(433bd9b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,D/PMS     (  905): acquireWL(438fcee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{435fc380: PendingIntentRecord{437f9c20 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228612, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4737 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{42695980: PendingIntentRecord{423f3048 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453043085022, Int=10800000
,D/PMS     (  905): releaseWL(438fcee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4737/10047)
,D/Process (  905): killProcessQuiet, pid=4381
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4381:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4381
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2220/10028)
,D/PMS     (  905): acquireWL(43917810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{432b61f0: PendingIntentRecord{437f9c20 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231852, Int=0
,D/PMS     (  905): releaseWL(43917810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 76:04:2b:1b:09:43 freq=2437 level=-90
D/wpa_supplicant( 1175): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=104 entropy=92
D/wpa_supplicant( 1175): Add randomness: count=105 entropy=93
D/wpa_supplicant( 1175): Add randomness: count=106 entropy=94
D/wpa_supplicant( 1175): Add randomness: count=107 entropy=95
D/wpa_supplicant( 1175): Add randomness: count=108 entropy=96
D/wpa_supplicant( 1175): Add randomness: count=109 entropy=97
D/wpa_supplicant( 1175): Add randomness: count=110 entropy=98
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_i,e_len=0 caps=0x411
D/wpa_supplicant( 1175): 3: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 6: 76:04:2b:1b:09:43 ssid='Lenovo TAB 2 A7-30H' wpa_ie_len=0 rsn_ie_len=0 wapi_ie_len=0 caps=0x421
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (7 BSSes)
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 76:04:2b:1b:09:43 freq=2437 level=-90
D/wpa_supplicant( 1175): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=111 entropy=99
D/wpa_supplicant( 1175): Add randomness: count=112 entropy=100
D/wpa_supplicant( 1175): Add randomness: count=113 entropy=101
D/wpa_supplicant( 1175): Add randomness: count=114 entropy=102
D/wpa_supplicant( 1175): Add randomness: count=115 entropy=103
D/wpa_supplicant( 1175): Add randomness: count=116 entropy=104
D/wpa_supplicant( 1175): Add randomness: count=117 entropy=105
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
,W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1175): reply (1025) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000235194132
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000131034197
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000235194159
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-82
I/wpa_supplicant( 1175): tsf=0000000235194170
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000235194209
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000235194190
I/wpa_supplicant( 1175): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=UPC Wi-Free
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=8
I/wpa_supplicant( 1175): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000235194199
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=UPC5999698
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=9
,I/wpa_supplicant( 1175): bssid=76:04:2b:1b:09:43
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-90
I/wpa_supplicant( 1175): tsf=0000000235194179
I/wpa_supplicant( 1175): flags=[WPS][ESS]
I/wpa_supplicant( 1175): ss
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiP2pService(  905): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 235194132, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 131034197, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 235194159, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 235194170, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 235194209, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 235194190, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 235194199, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: Lenovo TAB 2 A7-30H, BSSID: 76:04:2b:1b:09:43, capabilities: [WPS][ESS], level: -90, frequency: 2437, timestamp: 235194179, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 8 to mScanResults,
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  68, AP:              Lenovo TAB 2 A7-30H [76:04:2b:1b:09:43], Rssi:  0 [-90], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (8) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(426d7a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42274050: PendingIntentRecord{420d5800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=235480, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(426d7a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(43c94550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c94550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1175): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=118 entropy=106
D/wpa_supplicant( 1175): Add randomness: count=119 entropy=107
D/wpa_supplicant( 1175): Add randomness: count=120 entropy=108
D/wpa_supplicant( 1175): Add randomness: count=121 entropy=109
D/wpa_supplicant( 1175): Add randomness: count=122 entropy=110
D/wpa_supplicant( 1175): Add randomness: count=123 entropy=111
D/wpa_supplicant( 1175): Add randomness: count=124 entropy=112
D/wpa_supplicant( 1175): Add randomness: count=125 entropy=113
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 5: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 7: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1175): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=126 entropy=114
D/wpa_supplicant( 1175): Add randomness: count=127 entropy=115
D/wpa_supplicant( 1175): Add randomness: count=128 entropy=116
D/wpa_supplicant( 1175): Add randomness: count=129 entropy=117
D/wpa_supplicant( 1175): Add randomness: count=130 entropy=118
D/wpa_supplicant( 1175): Add randomness: count=131 entropy=119
D/wpa_supplicant( 1175): Add randomness: count=132 entropy=120
D/wpa_supplicant( 1175): Add randomness: count=133 entropy=121
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extensio,n (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1175): reply (1171) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000252593894
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
,I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000252593922
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000252593934
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427,
I/wpa_supplicant( 1175): level=-79
I/wpa_supplicant( 1175): tsf=0000000252593944
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000252593985
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
,I/wpa_supplicant( 1175): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000252593953
I/wpa_supplicant( 1175): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=UPC Wi-Free
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=8
I/wpa_supplicant( 1175): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000252593963
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=UPC5999698
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=9
I/wpa_supplicant( 1175): bssid=76:04:2b:1b:09:43
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-90
I/wpa_supplicant( 1175): tsf=0000000235194179
I/wpa_supplicant( 1175): flags=[WPS][ESS]
I/wpa_supplicant( 1175): ss
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 252593894, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 252593922, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 252593934, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 252593944, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 252593985, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 252593953, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 252593963, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: Lenovo TAB 2 A7-30H, BSSID: 76:04:2b:1b:09:43, capabilities: [WPS][ESS], level: -90, frequency: 2437, timestamp: 235194179, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 8: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 252593973, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 9 to mScanResults
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0,
V/ScoreHelper(  905):  + ScoreResult:  70, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:              Lenovo TAB 2 A7-30H [76:04:2b:1b:09:43], Rssi:  0 [-90], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (9) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(424ce680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000},
,V/AlarmManager(  905): sending alarm PendingIntent{41d1f120: PendingIntentRecord{424c0b00 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=254339, Int=0
,D/PMS     (  905): acquireWL(43812e48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): releaseWL(424ce680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43132d18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43812e48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(43132d18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
D/wpa_supplicant( 1175): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=134 entropy=122
D/wpa_supplicant( 1175): Add randomness: count=135 entropy=123
D/wpa_supplicant( 1175): Add randomness: count=136 entropy=124
D/wpa_supplicant( 1175): Add randomness: count=137 entropy=125
D/wpa_supplicant( 1175): Add randomness: count=138 entropy=126
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplican,t( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
D/wpa_supplicant( 1175): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=139 entropy=127
D/wpa_supplicant( 1175): Add randomness: count=140 entropy=128
D/wpa_supplicant( 1175): Add randomness: count=141 entropy=129
D/wpa_supplicant( 1175): Add randomness: count=142 entropy=130
D/wpa_supplicant( 1175): Add randomness: count=143 entropy=131
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1175): reply (1054) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000252593894
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000269964157
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000269964169
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-82
I/wpa_supplicant( 1175): tsf=0000000269964179
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000269964188
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
,I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000252593953
I/wpa_supplicant( 1175): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=UPC Wi-Free
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=8
I/wpa_supplicant( 1175): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000252593963
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=UPC5999698
I/wpa_supplicant( 1175): ====
,I/wpa_supplicant( 1175): id=10
I/wpa_supplicant( 1175): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000252593973
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CC
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 252593894, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 269964157, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 269964169, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 269964179, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 269964188, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
,D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 252593953, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 252593963, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 252593973, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  905): add 8 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList,
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  72, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  72, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (8) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1175): [NULL] 8e:04:ff:b9:af:27 freq=2462 level=-90
I/wpa_supplicant( 1175): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
D/wpa_supplicant( 1175): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=144 entropy=132
D/wpa_supplicant( 1175): Add randomness: count=145 entropy=133
D/wpa_supplicant( 1175): Add randomness: count=146 entropy=134
D/wpa_supplicant( 1175): Add randomness: count=147 entropy=135
D/wpa_supplicant( 1175): Add randomness: count=148 entropy=136
D/wpa_supplicant( 1175): Add randomness: count=149 entropy=137
D/wpa_supplicant( 1175): Add randomness: count=150 entropy=138
D/wpa_supplicant( 1175): Add randomness: count=151 entropy=139
D/wpa_supplicant( 1175): Add randomness: count=152 entropy=140
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa,_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 6: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 7: 8e:04:ff:b9:af:27 ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1175): 8: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1175): [NULL] 8e:04:ff:b9:af:27 freq=2462 level=-90
I/wpa_supplicant( 1175): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
D/wpa_supplicant( 1175): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=153 entropy=141
D/wpa_supplicant( 1175): Add randomness: count=154 entropy=142
D/wpa_supplicant( 1175): Add randomness: count=155 entropy=143
D/wpa_supplicant( 1175): Add randomness: count=156 entropy=144
D/wpa_supplicant( 1175): Add randomness: count=157 entropy=145
D/wpa_supplicant( 1175): Add randomness: count=158 entropy=146
D/wpa_supplicant( 1175): Add randomness: count=159 entropy=147
D/wpa_supplicant( 1175): Add randomness: count=160 entropy=148
D/wpa_supplicant( 1175): Add randomness: count=161 entropy=149
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplica,nt( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1175): reply (1164) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000287354915
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000287354942
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000287354953
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-78
I/wpa_supplicant( 1175): tsf=0000000287354963
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-88
,I/wpa_supplicant( 1175): tsf=0000000269964188
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-90
I/wpa_supplicant( 1175): tsf=0000000287354973
I/wpa_supplicant( 1175): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=UPC Wi-Free
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=8
I/wpa_supplicant( 1175): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-90
I/wpa_supplicant( 1175): tsf=0000000287354983
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=UPC5999698
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=11
I/wpa_supplicant( 1175): bssid=8e:04:ff:b9:af:27
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-90
I/wpa_supplicant( 1175): tsf=0000000287354994
I/wpa_supplicant( 1175): flags=[WPA2-EAP-CC
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 287354915, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 287354942, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 287354953, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0,
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 287354963, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 269964188, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 287354973, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 287354983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC Wi-Free, BSSID: 8e:04:ff:b9:af:27, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 287354994, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 8: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 287355013, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 9 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  75, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [8e:04:ff:b9:af:27], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  68, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  68, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  68, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-91], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (9) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43403490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42274050: PendingIntentRecord{420d5800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=295480, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43403490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
I/wpa_supplicant( 1175): [NULL] 8e:04:ff:b9:af:27 freq=2462 level=-90
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1175): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
D/wpa_supplicant( 1175): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=162 entropy=150
D/wpa_supplicant( 1175): Add randomness: count=163 entropy=151
D/wpa_supplicant( 1175): Add randomness: count=164 entropy=152
D/wpa_supplicant( 1175): Add randomness: count=165 entropy=153
D/wpa_supplicant( 1175): Add randomness: count=166 entropy=154
D/wpa_supplicant( 1175): Add randomness: count=167 entropy=155
D/wpa_supplicant( 1175): Add randomness: count=168 entropy=156
D/wpa_supplicant( 1175): Add randomness: count=169 entropy=157
D/wpa_supplicant( 1175): Add randomness: count=170 entropy=158
D/wpa_supplicant( 1175): Add randomness: count=171 entropy=159
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplic,ant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 5: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 6: 8e:04:ff:b9:af:27 ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1175): 7: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 8: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 9: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
I/wpa_supplicant( 1175): [NULL] 8e:04:ff:b9:af:27 freq=2462 level=-90
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1175): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
D/wpa_supplicant( 1175): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=172 entropy=160
D/wpa_supplicant( 1175): Add randomness: count=173 entropy=161
D/wpa_supplicant( 1175): Add randomness: count=174 entropy=162
D/wpa_supplicant( 1175): Add randomness: count=175 entropy=163
D/wpa_supplicant( 1175): Add randomness: count=176 entropy=164
D/wpa_supplicant( 1175): Add randomness: count=177 entropy=165
D/wpa_supplicant( 1175): Add randomness: count=178 entropy=166
D/wpa_supplicant( 1175): Add randomness: count=179 entropy=167
D/wpa_supplicant( 1175): Add randomness: count=180 entropy=168
D/wpa_supplicant( 1175): Add randomness: count=181 entropy=169
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Exten,sion (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1175): reply (1310) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-48
I/wpa_supplicant( 1175): tsf=0000000304754266
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=N,G7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000304754293
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000304754305
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-81
I/wpa_supplicant( 1175): tsf=0000000304754315
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000269964188
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-90
I/wpa_supplicant( 1175): tsf=0000000304754324
I/wpa_supplicant( 1175): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=UPC Wi-Free
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=8
I/wpa_supplicant( 1175): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-91
I/wpa_supplicant( 1175): tsf=0000000304754377
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=UPC5999698
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=11
I/wpa_supplicant( 1175): bssid=8e:04:ff:b9:af:27
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-90
I/wpa_supplicant( 1175): tsf=0000000304754334
I/wpa_supplicant( 1175): flags=[WPA2-EAP-CC
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): InactiveState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 304754266, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 304754293, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 304754305, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 304754315, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  ,905): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 269964188, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 304754324, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 304754377, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/WifiStateMachine(  905): 7: scan result = SSID: UPC Wi-Free, BSSID: 8e:04:ff:b9:af:27, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 304754334, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 8: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 304754367, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 9: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 304754344, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 10 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  75, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [8e:04:ff:b9:af:27], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  66, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-91], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (10) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42285b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42285b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
,D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1175): [NULL] 8e:04:ff:b9:af:27 freq=2462 level=-90
I/wpa_supplicant( 1175): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-90
I/wpa_supplicant( 1175): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
D/wpa_supplicant( 1175): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=182 entropy=170
D/wpa_supplicant( 1175): Add randomness: count=183 entropy=171
D/wpa_supplicant( 1175): Add randomness: count=184 entropy=172
D/wpa_supplicant( 1175): Add randomness: count=185 entropy=173
D/wpa_supplicant( 1175): Add randomness: count=186 entropy=174
D/wpa_supplicant( 1175): Add randomness: count=187 entropy=175
D/wpa_supplicant( 1175): Add randomness: count=188 entropy=176
D/wpa_supplicant( 1175): Add randomness: count=189 entropy=177
D/wpa_supplicant( 1175): Add randomness: count=190 entropy=178
D/wpa_supplicant( 1175): Add randomness: count=191 entropy=179
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 9
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_s,tatus is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 0
I/wpa_supplicant( 1175): wpa_s->is_screen_on 0
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1175): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 6: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 7: 8e:04:ff:b9:af:27 ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1175): 8: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1175): 9: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1175): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (10 BSSes)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1175): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1175): [NULL] 8e:04:ff:b9:af:27 freq=2462 level=-90
I/wpa_supplicant( 1175): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-90
I/wpa_supplicant( 1175): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
D/wpa_supplicant( 1175): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=192 entropy=180
D/wpa_supplicant( 1175): Add randomness: count=193 entropy=181
D/wpa_supplicant( 1175): Add randomness: count=194 entropy=182
D/wpa_supplicant( 1175): Add randomness: count=195 entropy=183
D/wpa_supplicant( 1175): Add randomness: count=196 entropy=184
D/wpa_supplicant( 1175): Add randomness: count=197 entropy=185
D/wpa_supplicant( 1175): Add randomness: count=198 entropy=186
D/wpa_supplicant( 1175): Add randomness: count=199 entropy=187
D/wpa_supplicant( 1175): Add randomness: count=200 entropy=188
D/wpa_supplicant( 1175): Add randomness: count=201 entropy=189
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa,_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[5] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): clear disabled list - type=1
I/wpa_supplicant( 1175): No suitable network found
W/wpa_supplicant( 1175): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1175): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1175): reply (1424) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000322153873
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa,_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000322153900
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-60
I/wpa_supplicant( 1175): tsf=0000000322153910
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-81
I/wpa_supplicant( 1175): tsf=0000000322153920
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000269964188
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-89
I/wpa_supplicant( 1175): tsf=0000000322153940
I/wpa_supplicant( 1175): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=UPC Wi-Free
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=8
I/wpa_supplicant( 1175): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-90
I/wpa_supplicant( 1175): tsf=0000000322153960
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=UPC5999698
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=11
I/wpa_supplicant( 1175): bssid=8e:04:ff:b9:af:27
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-90
I/wpa_supplicant( 1175): tsf=0000000322153930
I/wpa_supplicant( 1175): flags=[WPA2-EAP-CC
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 322153873, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 322153900, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 322153910, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 322153920, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 269964188, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 322153940, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 322153960, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC Wi-Free, BSSID: 8e:04:ff:b9:af:27, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 322153930, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0,
D/WifiStateMachine(  905): 8: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 322153980, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 9: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 304754344, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 10: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -90, frequency: 2412, timestamp: 322153949, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 11 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0,
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [8e:04:ff:b9:af:27], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-90], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (11) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/jxcore-log( 4419): --= Surplus to requirements =--,
I/jxcore-log( 4419): 
I/jxcore-log( 4419): ****TEST TOOK:  ms ****
I/jxcore-log( 4419): 
,I/jxcore-log( 4419): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 4419): 
,E/cutils-trace( 4758): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4758): ====startRecUseTime====
D/htc.customization.log.level( 4758):  is 
,W/CustomizationLogLevel( 4758): Level value is invalid, use default level 2
,D/CustomizationManager( 4758):  Read ACC file spent 0.105 (s)
D/CIDMapFileReader( 4758): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4758): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4758): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4758): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4758): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4758): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4758): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4758): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4758): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4758): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4758): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4758): Parsing tag category name = system
,I/CustomizationCIDLoader( 4758): Parsing tag category name = application
I/CustomizationCIDLoader( 4758): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 4758): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4758): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4758): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4758): Parsing tag category name = Settings
,D/CustomizationManager( 4758):  Read CID file spent 0.159 (s)
,D/CustomizationManager( 4758):  All configurations done spent 0.160 (s)
W/HtcNativeFlag( 4758): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4758): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4758): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4758): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4758, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4419
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  905): Killing 4419:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905):   Force finishing activity ActivityRecord{423e6468 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  905): Copying FileAsset 0x62e91f28 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4419 uid 10189
E/JavaBinder( 1204): !!! FAILED BINDER TRANSACTION !!!
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/dalvikvm-heap( 4160): Grow heap (frag case) to 13.529MB for 1821008-byte allocation
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1605): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,D/DotMatrix( 1605): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1888): Unregistering com.test.thalitest
,E/acms    ( 1888): Could not unregister removed application com.test.thalitest
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  905): WIN DEATH: Window{42553cd0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  905): Client connection lost with reason: 4
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  905): acquireWL(4245a320): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/GeofencerStateMachine( 1434): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/Launcher( 1269): Deferring update until onResume
,D/Launcher( 1269): waitUntilResume // bindAppsRemoved
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,D/PackageBroadcastService( 2220): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PMS     (  905): releaseWL(4245a320): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4774 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/MultiDex( 4774): install
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/ActivityManager(  905): Delaying start of: ServiceRecord{43114da0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/MultiDex( 4774): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/MultiDex( 4774): loading existing secondary dex files
,I/MultiDex( 4774): load found 1 secondary dex files
,I/MultiDex( 4774): install done
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1331): Unsupported attribute readOnly
,I/PeopleContactsSync( 2220): CP2 sync disabled
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2220, uid=10028, userID:0
,D/PMS     (  905): acquireWL(441ef700): PARTIAL_WAKE_LOCK  Icing 0x1 2220 10028 null
I/Icing   ( 2220): doRemovePackageData com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  905): releaseWL(441ef700): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4792 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ProviderInstaller( 4774): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4792): install
,I/MultiDex( 4792): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4792): loading existing secondary dex files
,I/MultiDex( 4792): load found 1 secondary dex files
,I/MultiDex( 4792): install done
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ProviderInstaller( 4792): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1402): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1402): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4295
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  905): Killing 4295:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/IcingCorporaProvider( 2910): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  905): Recipient 4295
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4810 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  905): acquireWL(42377348): PARTIAL_WAKE_LOCK  Icing 0x1 2220 10028 null
,I/IcingCorporaProvider( 2910): UpdateCorporaTask done [took 158 ms] updated apps [took 157 ms] 
,E/SQLiteLog( 4774): (3850) statement aborts at 134: [DELETE FROM FileContent24 WHERE hash IN WipeoutFileContentHashView] disk I/O error
,E/SQLiteDBG( 4774): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c927888
,E/DocListDatabase( 4774): Failed to delete from FileContent24
E/DocListDatabase( 4774): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4774): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4774): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4774): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4774): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4774): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4774): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4774): 	at cva.j(SourceFile:1094)
E/DocListDatabase( 4774): 	at chh.run(SourceFile:272)
E/DocListDatabase( 4774): 	at crv.run(SourceFile:48)
E/DocListDatabase( 4774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 4774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 4774): 	at java.lang.Thread.run(Thread.java:864)
W/PackageManager(  905): Unable to load service info ResolveInfo{4245b460 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4774): threadid=12: thread exiting with uncaught exception (group=0x416eee30)
,E/AndroidRuntime( 4774): FATAL EXCEPTION: pool-4-thread-1
E/AndroidRuntime( 4774): Process: com.google.android.gms.drive, PID: 4774
E/AndroidRuntime( 4774): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4774): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4774): 	at cva.j(SourceFile:1094)
E/AndroidRuntime( 4774): 	at chh.run(SourceFile:272)
E/AndroidRuntime( 4774): 	at crv.run(SourceFile:48)
E/AndroidRuntime( 4774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4774): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
D/Process ( 4774): killProcess, pid=4774
,D/Process ( 4774): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,E/SQLiteDatabase( 4810): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4810): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4810): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4810): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4810): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4810): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4810): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4810): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4810): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4810): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4810): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4810): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4810): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4810): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4810): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4810): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4810): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4810): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4810): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4810): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4810): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4810): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4810): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4810): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4810): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4810): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4810): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4810): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4810): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4810): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4810): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4810): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4810): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4810): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4810): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4810): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4810): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4810): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4810): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4810): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4810): Opened ClientFlag.db in read-only mode
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/SQLiteDatabase( 4810): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4810): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4810): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4810): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4810): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4810): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4810): threadid=11: thread exiting with uncaught exception (group=0x416eee30)
,E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4810): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4810): Process: com.google.android.apps.docs, PID: 4810
E/AndroidRuntime( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4810): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4810): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4810): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4810): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4810): 	at aho.run(AbstractDatabaseInstance.java:455)
I/ActivityManager(  905): Recipient 4774
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4774) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
,E/SQLiteDatabase( 4810): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4810): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4810): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4810): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4810): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4810): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4810): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4810): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4810): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4810): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4810): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4810): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4810): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4810): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4810): ,	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4810): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4810): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4810): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4810): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4810): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4810): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4810): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4810): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4810): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4810): Opened ClientFlag.db in read-only mode
,I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4834 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4810): killProcess, pid=4810
D/Process ( 4810): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  905): Recipient 4810
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=4466
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4466:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4810) has died.
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4466
,W/ContextImpl( 4834): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4834): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4834): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4834): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4834): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4834): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4834): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4834): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4834): threadid=10: thread exiting with uncaught exception (group=0x416eee30)
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4848 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/AndroidRuntime( 4834): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4834): Process: com.android.keychain, PID: 4834
E/AndroidRuntime( 4834): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4834): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4834): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4834): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4834): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4834): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4834): killProcess, pid=4834
,D/Process ( 4834): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453043193950.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
,I/ActivityManager(  905): Recipient 4834
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4834) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10787ms
,D/AppTag  ( 4848): getInstance(Context context)
,D/AppTag  ( 4848): getInstance(Context context)
,D/AppTag  ( 4848): onCreate()
,I/dalvikvm-heap( 4160): Grow heap (frag case) to 15.220MB for 1821008-byte allocation
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4864 uid=10098 gids={50098, 3003, 5012}
D/PMS     (  905): acquireWL(42f3ee40): PARTIAL_WAKE_LOCK  AsyncService 0x1 4160 10160 null
,I/dalvikvm-heap( 4160): Grow heap (frag case) to 16.956MB for 1821008-byte allocation
D/PMS     (  905): releaseWL(42f3ee40): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/DeviceManagement( 4864): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4864 dbg=false s=true
,I/DeviceManagement( 4864): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4864): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4864): WorkflowService: Starting workflow service
I/DeviceManagement( 4864): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b54270] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4864): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4864): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4864): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4864): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4881 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4864): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4864): SessionStateController: Checking invariants...
,D/Documents( 4881): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4881): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4881): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4881): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4881): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4881): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4881): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4881): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4881): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4881): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4881): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4881): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4881): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4881): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4881): threadid=1: thread exiting with uncaught exception (group=0x416eee30)
E/AndroidRuntime( 4881): FATAL EXCEPTION: main
E/AndroidRuntime( 4881): Process: com.android.documentsui, PID: 4881
E/AndroidRuntime( 4881): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4881): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4881): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4881): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4881): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4881): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4881): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4881): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4881): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4881): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4881): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4881): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4881): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4881): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4881): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4881): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4881): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4881): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4881): 	... 10 more
I/ActivityManager(  905): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4895 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  905): killProcessQuiet, pid=3901
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/ActivityManager(  905): App crashed! Process: com.android.documentsui
I/ActivityManager(  905): Killing 3901:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453043194227.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
,D/Process (  905): killProcessQuiet, pid=4517
I/ActivityManager(  905): Killing 4517:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  905): Recipient 3901
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.music (pid 3901): Died!
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/Process ( 4881): killProcess, pid=4881
,D/Process ( 4881): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Recipient 4517
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Recipient 4881
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  905): Process com.android.documentsui (pid 4881) has died.
,D/ExternalStorage( 4895): After updating volumes, found 1 active roots
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,E/SQLiteDatabase( 4864): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4864): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4864): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4864): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4864): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4864): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4864): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4864): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4864): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4864): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4864): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4864): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4864): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4864): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4864): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4864): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4864): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4864): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4864): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4913 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4864): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4864): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4864): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4864): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4864): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4864): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4864): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4864): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4864): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4864): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4864): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4864): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b54270]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4864): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4864): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4864): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4864): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4864): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4864): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4864): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4864): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4864): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4864): WorkflowService: Stopping workflow service
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41bb3fb0 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,E/SQLiteDatabase( 4913): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4913): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4913): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4913): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4913): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4913): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4913): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4913): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4913): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4913): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4913): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4913): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4913): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4913): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4913): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4913): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4913): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4913): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4913): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4913): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4913): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4913): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4913): Opened MyDB.db in read-only mode
,I/ActivityManager(  905): Killing 4533:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=4533
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4533
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2220): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
,E/Icing   ( 2220): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,E/Icing   ( 2220): Could not init tag ds.tag.deleted

```
