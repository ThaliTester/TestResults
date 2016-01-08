#### Test 549702613245198_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Waited long enough for: ServiceRecord{445bf950 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4432): Error opening trace file: No such file or directory (2)
I/SensorManager(  906): mEventCount = 1050
D/CustomizationManager( 4432): ====startRecUseTime====
D/htc.customization.log.level( 4432):  is 
W/CustomizationLogLevel( 4432): Level value is invalid, use default level 2
D/CustomizationManager( 4432):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4432): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4432): Parsing tag category name = system
I/CustomizationCIDLoader( 4432): Parsing tag category name = application
I/CustomizationCIDLoader( 4432): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4432): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4432): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4432): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4432): Parsing tag category name = Settings
D/CustomizationManager( 4432):  Read CID file spent 0.109 (s)
D/CustomizationManager( 4432):  All configurations done spent 0.109 (s)
W/HtcNativeFlag( 4432): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4432): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4432): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4432): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4432
D/PMS     (  906): acquireHCC(42d2e1d0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(42ce2f58): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x69ff7f28 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1121614336
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4255dfc0
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  906): acquireWL(42c1cd78): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4443 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 4443): Copying FileAsset 0x5c7b2428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4443): Binding Chromium to main looper Looper (main, tid 1) {423fa5b0}
I/LibraryLoader( 4443): Expected native library version number "",actual native library version number ""
I/chromium( 4443): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4443): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(42bdb500): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): acquireWL(42b52be0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@429cf978:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4443): 1111556072: getState(). Returning 12
D/PMS     (  906): releaseWL(42bdb500): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4443): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4443): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4443): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4443): Local Branch: 
I/Adreno-EGL( 4443): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4443): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4443):                  aa63bbd948f41d15fc72f585e
W/chromium( 4443): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4443): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4443): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4443): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4443): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4443): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4443): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4443): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4443): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4443): CordovaWebView is running on device made by: HTC
,W/AwContents( 4443): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1272
W/ResourceType( 4443): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4443): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@42441698, mServedView=org.apache.cordova.engine.SystemWebView{42407300 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 4443): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Enable input method client, pid=4443
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +314ms
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  906): releaseWL(42c1cd78): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4443): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4443): JniHelper::setJavaVM(0x41fb6010), pthread_self() = 1662834472
D/JX-Cordova( 4443): jxcore cordova android initializing
D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 11.582MB for 95956-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 11.661MB for 143930-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 11.776MB for 215890-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 11.956MB for 323830-byte allocation
,D/PMS     (  906): acquireWL(42e6e918): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 12.223MB for 485740-byte allocation
D/PMS     (  906): releaseWL(42e6e918): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42f057f0): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(42f057f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(428e8d30): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(428e8d30): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42f20b48): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(42f20b48): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 13.233MB for 1092904-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 14.132MB for 1639352-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 15.458MB for 2459024-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(42d2e1d0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(42ce2f58): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 17.568MB for 3688532-byte allocation
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4492 uid=10077 gids={50077}
D/PMS     (  906): acquireWL(428a7748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{42ca6d50: PendingIntentRecord{42ce34f8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452283693405, Int=60000
,D/PMS     (  906): releaseWL(428a7748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4492): SMSBackupAgentService started
,D/SMSBackup( 4492): Checking restore status
D/SMSBackup( 4492): Restore complete
,D/SMSBackup( 4492): cancelCheckAlarm
,D/SMSBackup( 4492): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3679
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3679:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3679
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/jxcore-log( 4443): Initializing JXcore engine
,W/jxcore-log( 4443): JXcore engine is ready
,W/jxcore-log( 4443): Starting JXcore engine
,W/jxcore-log( 4443): Platform android
W/jxcore-log( 4443): 
,W/jxcore-log( 4443): Process ARCH arm
W/jxcore-log( 4443): 
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): releaseWL(42b52be0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4443): JXcore Cordova bridge is ready!
I/jxcore-log( 4443): 
W/jxcore-log( 4443): JXcore engine is started
,I/chromium( 4443): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4443): Toggling radios to true
I/jxcore-log( 4443): 
,D/BluetoothAdapter( 4443): enable(): BT is already enabled..!
,D/WifiManager( 4443): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1434
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
,W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
,D/WifiManager( 4443): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
,D/WifiManager( 4443): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): TDLS: Tear down peers
,I/wpa_supplicant( 1155): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4443, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4443): Radios toggled
I/jxcore-log( 4443): 
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1155): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1155): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1155): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb79bfbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1155):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1155): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1155): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (0)+
,D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0,
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1155): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1155): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/PMS     (  906): acquireWL(42dd6f38): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): Fast associate: Old scan results
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1155): wpa_supplicant_scan enter
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20134 mDataStallAlarmIntent=PendingIntent{42dc76c0: PendingIntentRecord{42d22510 android broadcastIntent}}
I/wpa_supplicant( 1155): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1840/10178)
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WISPrService( 4211): >>>>>WISPrService start isConnected = false<<<<<
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1840/10178)
D/WifiService(  906): New client listening to asynchronous messages
D/WISPrService( 4211): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4211): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4211): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/libc    (  363): [NET] entry_id:5   entry:0xb742bf98  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb742ffd8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7430248  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb742c190  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb74300e8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7430410  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb742c368  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  906): acquireWL(42ed4530): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(438cd530): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(438b7b10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  906): releaseWL(438b7b10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/WifiNative-wlan0(  906): doBoolean: SCAN
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1372/10028)
D/PMS     (  906): releaseWL(42ed4530): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): releaseWL(438cd530): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
,I/Tethering(  906): No IPv4 upstream interface, giving up.
I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,I/NetworkMonitor( 3921): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(43840100): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/PMS     (  906): releaseWL(43840100): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1879/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1455/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3921/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4333/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1840/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4333/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2425/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4513 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4513): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4513): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4513): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4513): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4513): Preparing secondary program dexes.
V/DexLibLoader( 4513): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4513): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4513): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4513): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4513): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4513): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4513): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4513): Dex already copied
D/OdexVerifier( 4513): Odex verification is skipped.
,V/DexLibLoader( 4513): Creating class loader
,V/DexLibLoader( 4513): Finished creating class loader
V/DexLibLoader( 4513): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4513): Dex already copied
D/OdexVerifier( 4513): Odex verification is skipped.
,V/DexLibLoader( 4513): Creating class loader
V/DexLibLoader( 4513): Finished creating class loader
V/DexLibLoader( 4513): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4513): Dex already copied
D/OdexVerifier( 4513): Odex verification is skipped.
V/DexLibLoader( 4513): Creating class loader
V/DexLibLoader( 4513): Finished creating class loader
,V/DexLibLoader( 4513): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4513): Dex already copied
D/OdexVerifier( 4513): Odex verification is skipped.
,V/DexLibLoader( 4513): Creating class loader
V/DexLibLoader( 4513): Finished creating class loader
V/DexLibLoader( 4513): Verifying classes from secondary dexes.
D/DexLibLoader( 4513): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4513): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4513): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4513): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4513): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4513): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4513): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4513): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1155): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1155): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1155): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1155): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 3
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 1
I/wpa_supplicant( 1155): wpa_s->is_screen_on 1
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): selected network = 1
D/wpa_supplicant( 1155): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb79c14e8  current_ssid=0x0
D/wpa_supplicant( 1155): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): supplicant attached completed, trigg,er assoc.
D/wpa_supplicant( 1155): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1155): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1155): check if in concurrent case
,I/wpa_supplicant( 1155): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
W/dalvikvm( 4513): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1155): RSN: PMKSA cache search - network_ctx=0xb79c14e8 try_opportunistic=0
D/wpa_supplicant( 1155): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 1155): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1155): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1155): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1155): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1155): nl80211: Unsubscribe mgmt frames handle 0xb79c0718 (mode change),
D/wpa_supplicant( 1155): nl80211: Subscribe to mgmt frames with non-AP handle 0xb79c0718
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb79c0718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb79c0718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb79c0718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb79c0718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb79c0718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb79c0718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb79c0718
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb79c0718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb79c0718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb79c0718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1155):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1155):   * freq=2412
D/wpa_supplicant( 1155):   * Auth Type 0
D/wpa_supplicant( 1155):   * WPA Versions 0x2
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1155): nl80211: Connect request send successfully
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (636) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-48
I/wpa_supplicant( 1155): tsf=0000000108081180
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000108081197
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000108081201
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====,
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000108081192
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000108081204
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 108081180, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 108081197, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 108081201, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 108081192, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 108081204, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/dalvikvm( 4513): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1155): nl80211: Connect event
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1155): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1155): Add randomness: count=11 entropy=5
I/wpa_supplicant( 1155): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1155): TDLS: Remove peers on association
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1155): EAPOL: enable timer tick
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1155): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1155): Get randomness: len=32 entropy=6
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
,D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiApDatabaseHandler(  906): updateConnectedAP...,
I/wpa_supplicant( 1155): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb79c09f0 key_idx=0 set_tx=1 seq_len=6 key_len=16,
D/wpa_supplicant( 1155):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1155): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f53b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1155):    broadcast key
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1155): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1155): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1155): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1155): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=6
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
I/wpa_supplicant( 1155): set send_ind_to_ndc = 0
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0,
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1155): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): This record is existed, only update it...,
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1155): EAPOL authentication completed successfully
I/wpa_supplicant( 1155): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WISPrService( 4211): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4211): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,E/FbInjectorInitializer( 4513): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42a0e9e0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
,D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 1
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d7ca20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d7ca20 target=com.android.internal.util.StateMachine$SmHandler }
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4513): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4513): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4513): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3118
,I/ActivityManager(  906): Killing 3118:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PMS     (  906): acquireWL(43a5ab30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
I/ActivityManager(  906): Recipient 3118
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43b329c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(43a5ab30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  906): releaseWL(43b329c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/AutoSetting( 1417): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4542 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1417/10053)
,D/AutoSetting( 1417): Util - no network available!
,D/AutoSetting( 1417): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1417): service - mHandler: cancel location update
,D/AutoSetting( 1417): service -           changes count: 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1417/10053)
,W/fb4a(:<default>):UserScope( 4513): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4513): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4513): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4542): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4542): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4542): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4542): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4557 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3903
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3903:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4542/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4542/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4542/10078)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4513): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/Process (  906): killProcessQuiet, pid=4273
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4574 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 4273:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 9.958MB for 84664-byte allocation
,I/ActivityManager(  906): Recipient 3903
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4574): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4574): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4574): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4574): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 9.974MB for 28144-byte allocation
E/dalvikvm( 4513): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4513): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4513): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4513): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4513): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4513): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4513): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4513): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4513): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/ContextImpl( 4574): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/dalvikvm( 4513): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4513): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4513): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/dalvikvm( 4513): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4513): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4513): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4513): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4513): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4513): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4273
D/WifiService(  906): Client connection lost with reason: 4
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 10.039MB for 39954-byte allocation
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 10.115MB for 79892-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4574/10151)
,V/WebViewChromiumFactoryProvider( 4574): Binding Chromium to main looper Looper (main, tid 1) {423ff2d8}
,I/LibraryLoader( 4574): Expected native library version number "",actual native library version number ""
,I/chromium( 4574): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4574): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(44435298): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  906): acquireWL(444be8e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4574): BLUETOOTH permission is missing!
D/PMS     (  906): releaseWL(44435298): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4574): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4574): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4574): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4574): Local Branch: 
I/Adreno-EGL( 4574): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4574): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4574):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4574): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4574/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4574/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
,D/Process (  906): killProcessQuiet, pid=4302
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 10.281MB for 75760-byte allocation
I/ActivityManager(  906): Killing 4302:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1840/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1840/10178)
I/ActivityManager(  906): Recipient 4302
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4407c170 u0 ReceiverList{4407c130 4513 com.facebook.katana/10026/u0 remote:44015fe8}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4407c170 u0 ReceiverList{4407c130 4513 com.facebook.katana/10026/u0 remote:44015fe8}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44537288 u0 ReceiverList{44537228 4513 com.facebook.katana/10026/u0 remote:4452bbf8}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/PMS     (  906): acquireWL(42e280f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1455 10028 null
,D/PMS     (  906): releaseWL(42e280f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1455): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(43adbf60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1455 10028 null
D/PMS     (  906): releaseWL(43adbf60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1155): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1155): EAPOL: disable timer tick
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4513): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4513): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(42a0e9e0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20136 delay=15s
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 4211): >>>>>WISPrService start isConnected = true<<<<<
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1840/10178)
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@42d270a8
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
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
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
D/PMS     (  906): acquireWL(4404f4e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4542/10078)
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  906): acquireWL(43d7ef38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
D/PMS     (  906): acquireWL(43f6f5c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
D/PMS     (  906): releaseWL(43d7ef38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,I/CheckinService( 1226): Preparing to send checkin request
,I/EventLogService( 1226): Accumulating logs since 1452283645468
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1226): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1226): Using GMS GoogleHttpClient
D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
,D/PMS     (  906): releaseWL(4404f4e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1571): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{428d87b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 17 3 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4649 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4649): install
,I/MultiDex( 4649): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4649): loading existing secondary dex files
,I/MultiDex( 4649): load found 1 secondary dex files
,I/MultiDex( 4649): install done
,I/ProviderInstaller( 4649): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4649): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4649): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4649): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4649): Local Branch: 
I/Adreno-EGL( 4649): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4649): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4649):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): releaseWL(42dd6f38): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1455/10028)
D/PMS     (  906): acquireWL(43e9d4d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
V/Tethering(  906): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4333/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4542/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1840/10178)
I/acms    ( 1879): Checking Certificates
I/acms    ( 1879): Checking Developer Certificates
,I/acms    ( 1879): Checking Application Certificates
,I/acms    ( 1879): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1879): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1879): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1879): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1879): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1879): Updating next query delay: 75600000
I/mlserverapp( 1879): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1879): cancelACMSProgrammedChecks
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 3921): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4333/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1879/1000)
D/PMS     (  906): releaseWL(43e9d4d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3956/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3921/10154)
D/PMS     (  906): acquireWL(43970940): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43970940): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2425/10021)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1155): Change stage from stage0 to stage3
I/wpa_supplicant( 1155): wlan0: Background scan every 600 seconds
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42c6e808): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
D/PMS     (  906): releaseWL(42c6e808): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1372): [NET] getaddrinfo-, 1
D/libc    ( 1372): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/PMS     (  906): acquireWL(425afa98): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1372 10028 null
D/libc    (  363): [NET] +++++ res_nsend xid =dd28 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/AutoSetting( 1417): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4542): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4542): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1417/10053)
,D/AutoSetting( 1417): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4574/10151)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AutoSetting( 1417): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1417): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1417): service - onStartCommand() REMOVE current location bundle
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1417): service - handleMessage() setting current location null
D/AutoSetting( 1417): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1417): service - onStartCommand() check timezone in 30000
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1417/10053)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1840/10178)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 218
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): acquireWL(42d4d2e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  906): releaseWL(42d4d2e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4649/10028)
,I/Adreno-EGL( 4649): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4649): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4649): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4649): Local Branch: 
I/Adreno-EGL( 4649): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4649): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4649):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4649): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4649): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4649): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4649): Local Branch: 
I/Adreno-EGL( 4649): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4649): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4649):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=33 [6][2][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-55 , oldRssi= -200
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/Settings( 4649): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/GCM     ( 1372): Connected
D/PMS     (  906): acquireWL(42c3a3d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): releaseWL(425afa98): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): releaseWL(42c3a3d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(42f69670): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
,I/CheckinTask( 1226): Sending checkin request (9008 bytes)
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f227 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/GCM     ( 1372): Message class mpf
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): releaseWL(42f69670): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(42f49d88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  906): releaseWL(42f49d88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 263
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
W/fb4a(:<default>):UserScope( 4513): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4513): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4513): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=7 [13][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(42f1f818): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42f1f818): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1571): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{4259c038 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 6 2 12
,I/CheckinTask( 1226): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1226): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  906): releaseWL(43f6f5c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 1226): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@42432168 that was originally bound here
E/ActivityThread( 1226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@42432168 that was originally bound here
E/ActivityThread( 1226): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1226): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1226): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1226): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1226): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1226): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1226): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1226): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1226): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1226): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1226): 	at bks.a(SourceFile:298)
E/ActivityThread( 1226): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1226): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1226): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1226): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1372): GCM config loaded
,D/PMS     (  906): releaseWL(444be8e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42aa2b00
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
,W/SensorService(  906): Active sensors: size = 2
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  906): setLight #0: color=#0
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42aa2b00, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42c2d6b8
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42c192b0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 387ms
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@448bdc08)
D/NfcService( 1253): ScreenObserver: OFF
D/NfcService( 1253): applyRouting - 0,
D/NfcService( 1253): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=4443
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(443e5258): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(443e5258): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMN     (  906): onScreenOn
,D/PMS     (  906): acquireWL(4330b100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4330b100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2425): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1253): applyRouting - 0
D/AutoSetting( 1417): receiver - intent: android.intent.action.USER_PRESENT
,D/MtpService( 2425): [MTP][onReceive]-
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,D/NfcService( 1253): applyRouting -2
,D/AutoSetting( 1417): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20137 delay=15s
D/PMS     (  906): acquireWL(44019978): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  906): releaseWL(44019978): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
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
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): SET_SCREEN_ON:On
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1155): BG scan when screen On
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): Match BG scan, scan!
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
D/WifiNative-wlan0(  906):    returned true
D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 4211): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4211): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4211): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4211): Cust_ConnectToPC   : spcsc>false
D/        ( 4211): Cust_ConnectToPC   : IPT>true
,D/        ( 4211): Cust_ConnectToPC   : Singel_USB>false
,V/SRS_Proc(  370): ParamSet string: screen_state=on
D/WIFI_ICON( 1117): WifiActivity: 1
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/Settings( 4211): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,E/SmartNS_Utility( 4211): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4211): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4211): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4211): onReceive:android.intent.action.USER_PRESENT
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/ContextImpl( 4211): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4211): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4211): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4211):  defaultType:0
,I/ClockThread( 1117): stop update clock
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/NetworkPolicy(  906): updateScreenOn: false
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4693 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =758b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
W/ContextImpl( 4693): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1813): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1813): onScreenOn: 1452283701699
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1813): onScreenOn: 1452283701699
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/PMS     (  906): acquireWL(42c280f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1455 10028 null
D/PMS     (  906): releaseWL(42c280f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/SmartSyncUtils( 4693): isEpsOn(), nState = 0
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42c2d6b8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42c2d6b8, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42c192b0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  906): acquireWL(43add908): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4693 1000 null
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(449292a8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43add908): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20137 mDataStallAlarmIntent=PendingIntent{43a5baa8: PendingIntentRecord{42d22510 android broadcastIntent}}
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): SET_SCREEN_ON:Off
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1155): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/PMS     (  906): acquireWL(4452e980): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
V/SRS_Proc(  370): ParamSet string: screen_state=off
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/SmartSyncUtils( 4693): getMobilePolicyEnabled, result = true
D/PMS     (  906): releaseWL(4452e980): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  906): killProcessQuiet, pid=4333
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  906): updateScreenOn: false
,I/ActivityManager(  906): Killing 4333:com.google.android.apps.docs/u0a100 (adj 15): empty #17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
D/ContactMessageStore( 1245): Background delete complete
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,D/SmartSyncUtils( 4693): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4693): getMobilePolicyEnabled, result = true
,W/ContextImpl( 4693): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4693): isEpsOn(), nState = 0
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42c192b0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42c192b0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42c192b0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42c192b0
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42e3a200 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42e3a200 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1417): service - mHandler: cancel location update
D/AutoSetting( 1417): service -           changes count: 0
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1813): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1813): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1813): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1813): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1813): onScreenOff
D/PMS     (  906): acquireWL(444e28e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1455 10028 null
D/PMS     (  906): releaseWL(444e28e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  906): Recipient 4333
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  906): Activity pause timeout for ActivityRecord{42c12aa0 u0 com.test.thalitest/.MainActivity t2}
,I/GAV2    ( 4574): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(4444c408): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1455 10028 null
,D/PMS     (  906): acquireWL(448551f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1455 10028 null
,D/PMS     (  906): releaseWL(4444c408): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(448551f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/jxcore-log( 4443): Test app app.js loaded
I/jxcore-log( 4443): 
,I/Choreographer( 4443): Skipped 530 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4443): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4443): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{42407300 VFEDH.C. .F....ID 0,0-720,1134 #64}
,D/PMS     (  906): releaseWL(449292a8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/chromium( 4443): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=12 entropy=0
D/wpa_supplicant( 1155): Add randomness: count=13 entropy=1
D/wpa_supplicant( 1155): Add randomness: count=14 entropy=2
D/wpa_supplicant( 1155): Add randomness: count=15 entropy=3
D/wpa_supplicant( 1155): Add randomness: count=16 entropy=4
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplica,nt( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=17 entropy=5
D/wpa_supplicant( 1155): Add randomness: count=18 entropy=6
D/wpa_supplicant( 1155): Add randomness: count=19 entropy=7
D/wpa_supplicant( 1155): Add randomness: count=20 entropy=8
D/wpa_supplicant( 1155): Add randomness: count=21 entropy=9
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x2198,7"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (636) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-48
I/wpa_supplicant( 1155): tsf=0000000115711758
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000115711795
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000115711805
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000108081192
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000115711815
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiP2pService(  906): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@448d6d78 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@448d6d78 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@448d6d78 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 115711758, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 115711795, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 115711805, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 108081192, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 115711815, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  79, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/Process (  906): killProcessQuiet, pid=4351
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4351:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4351
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4373
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4373:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4373
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 11.001MB for 27674-byte allocation
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 11.023MB for 41506-byte allocation
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 11.056MB for 62254-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4513/10026)
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 11.081MB for 72920-byte allocation
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 11.087MB for 73580-byte allocation
,I/dalvikvm-heap( 4513): Grow heap (frag case) to 11.125MB for 64742-byte allocation
,D/libc    ( 4513): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4513): [NET] getaddrinfo-,err=8
D/libc    ( 4513): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4513): [NET] getaddrinfo-, 1
,D/libc    ( 4513): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1b3a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=93
D/libc    (  363): [NET]res_queryN: exit 3, ancount=3
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4513): [NET] getaddrinfo_proxy-, success
I/global  ( 4513): call createSocket() return a new socket.
D/libc    ( 4513): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4513): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4513): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4513): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(44c194b0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4513 10026 null
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,I/global  ( 4513): I/O error closing connection
I/global  ( 4513): java.net.SocketException: Socket is closed
I/global  ( 4513): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4513): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4513): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4513): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4513): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4513): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4513): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4513): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4513): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4513): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4513): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4513): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4513): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4513): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4513): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4513): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4513): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4513): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4513): Removing a connection that never existed!
D/PMS     (  906): releaseWL(44c194b0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(44935b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44935b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=22 entropy=10
D/wpa_supplicant( 1155): Add randomness: count=23 entropy=11
D/wpa_supplicant( 1155): Add randomness: count=24 entropy=12
D/wpa_supplicant( 1155): Add randomness: count=25 entropy=13
D/wpa_supplicant( 1155): Add randomness: count=26 entropy=14
D/wpa_supplicant( 1155): Add randomness: count=27 entropy=15
D/wpa_supplicant( 1155): Add randomness: count=28 entropy=16
D/wpa_supplicant( 1155): Add randomness: count=29 entropy=17
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' ,wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=30 entropy=18
D/wpa_supplicant( 1155): Add randomness: count=31 entropy=19
D/wpa_supplicant( 1155): Add randomness: count=32 entropy=20
D/wpa_supplicant( 1155): Add randomness: count=33 entropy=21
D/wpa_supplicant( 1155): Add randomness: count=34 entropy=22
D/wpa_supplicant( 1155): Add randomness: count=35 entropy=23
D/wpa_supplicant( 1155): Add randomness: count=36 entropy=24
D/wpa_supplicant( 1155): Add randomness: count=37 entropy=25
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1069) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-48
I/wpa_supplicant( 1155): tsf=0000000115711758
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000133943478
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000133943488
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
,I/wpa_supplicant( 1155): tsf=0000000108081192
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000133943509
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-85
I/wpa_supplicant( 1155): tsf=0000000133943497
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462,
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000133943520
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000133943529
I/wpa_supplicant( 1155): flags
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 115711758, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 133943478, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 133943488, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 108081192, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 133943509, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 133943497, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 133943520, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 133943529, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1417): service - mHandler: update timezone
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found,
D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1519): service - onCreate()
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
,D/DotMatrix( 1571): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1571): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{424b0f78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 3 11
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/PMS     (  906): acquireWL(4364abf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  906): sending alarm PendingIntent{42dd0b88: PendingIntentRecord{42df3cc8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141753, Int=0
D/PMS     (  906): acquireWL(43643bc0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
V/AlarmManager(  906): sending alarm PendingIntent{4255f6c0: PendingIntentRecord{42b31b10 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143126, Int=0
,D/PMS     (  906): releaseWL(4364abf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/AutoSetting( 1417): service - handleMessage() stop self
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): acquireWL(42c651e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9b19 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  906): releaseWL(42c651e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1417): service - handleMessage() quit looper
,D/AutoSetting( 1417): service - onDestroy() END
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(43643bc0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  906): killProcessQuiet, pid=3956
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3956:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3956
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(42c6e138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429a4500: PendingIntentRecord{42740f28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=151266, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c6e138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=38 entropy=26
D/wpa_supplicant( 1155): Add randomness: count=39 entropy=27
D/wpa_supplicant( 1155): Add randomness: count=40 entropy=28
D/wpa_supplicant( 1155): Add randomness: count=41 entropy=29
D/wpa_supplicant( 1155): Add randomness: count=42 entropy=30
D/wpa_supplicant( 1155): Add randomness: count=43 entropy=31
D/wpa_supplicant( 1155): Add randomness: count=44 entropy=32
D/wpa_supplicant( 1155): Add randomness: count=45 entropy=33
D/wpa_supplicant( 1155): Add randomness: count=46 entropy=34
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1155): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
,D/wpa_supplicant( 1155): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=47 entropy=35
D/wpa_supplicant( 1155): Add randomness: count=48 entropy=36
D/wpa_supplicant( 1155): Add randomness: count=49 entropy=37
D/wpa_supplicant( 1155): Add randomness: count=50 entropy=38
D/wpa_supplicant( 1155): Add randomness: count=51 entropy=39
D/wpa_supplicant( 1155): Add randomness: count=52 entropy=40
D/wpa_supplicant( 1155): Add randomness: count=53 entropy=41
D/wpa_supplicant( 1155): Add randomness: count=54 entropy=42
D/wpa_supplicant( 1155): Add randomness: count=55 entropy=43
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-48
I/wpa_supplicant( 1155): tsf=0000000115711758
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000152183504
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-77
I/wpa_supplicant( 1155): tsf=0000000152183514
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000108081192
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-83
I/wpa_supplicant( 1155): tsf=0000000152183533
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-85
I/wpa_supplicant( 1155): tsf=0000000152183524
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000152183555
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000152183566
I/wpa_supplicant( 1155): flags
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 115711758, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 152183504, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 152183514, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 108081192, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -83, frequency: 2437, timestamp: 152183533, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 152183524, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 152183555, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 152183566, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 152183543, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-83], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{445bb930 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=56 entropy=44
D/wpa_supplicant( 1155): Add randomness: count=57 entropy=45
D/wpa_supplicant( 1155): Add randomness: count=58 entropy=46
D/wpa_supplicant( 1155): Add randomness: count=59 entropy=47
D/wpa_supplicant( 1155): Add randomness: count=60 entropy=48
D/wpa_supplicant( 1155): Add randomness: count=61 entropy=49
D/wpa_supplicant( 1155): Add randomness: count=62 entropy=50
D/wpa_supplicant( 1155): Add randomness: count=63 entropy=51
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 ,rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=64 entropy=52
D/wpa_supplicant( 1155): Add randomness: count=65 entropy=53
D/wpa_supplicant( 1155): Add randomness: count=66 entropy=54
D/wpa_supplicant( 1155): Add randomness: count=67 entropy=55
D/wpa_supplicant( 1155): Add randomness: count=68 entropy=56
D/wpa_supplicant( 1155): Add randomness: count=69 entropy=57
D/wpa_supplicant( 1155): Add randomness: count=70 entropy=58
D/wpa_supplicant( 1155): Add randomness: count=71 entropy=59
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( ,1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-48
I/wpa_supplicant( 1155): tsf=0000000170332003
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000170332031
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000152183514
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000108081192
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000170332060
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155):, level=-85
I/wpa_supplicant( 1155): tsf=0000000170332051
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000170332081
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000170332090
I/wpa_supplicant( 1155): flags
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 170332003, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 170332031, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 152183514, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 108081192, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 170332060, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 170332051, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 170332081, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 170332090, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 170332071, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4391
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 4391:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4391
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42f4ea40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42f4ea40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=72 entropy=60
D/wpa_supplicant( 1155): Add randomness: count=73 entropy=61
D/wpa_supplicant( 1155): Add randomness: count=74 entropy=62
D/wpa_supplicant( 1155): Add randomness: count=75 entropy=63
D/wpa_supplicant( 1155): Add randomness: count=76 entropy=64
D/wpa_supplicant( 1155): Add randomness: count=77 entropy=65
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1155): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
,D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
,I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=78 entropy=66
D/wpa_supplicant( 1155): Add randomness: count=79 entropy=67
D/wpa_supplicant( 1155): Add randomness: count=80 entropy=68
D/wpa_supplicant( 1155): Add randomness: count=81 entropy=69
,D/wpa_supplicant( 1155): Add randomness: count=82 entropy=70
D/wpa_supplicant( 1155): Add randomness: count=83 entropy=71
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
,I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1103) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000170332003
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000188523324
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000188523335
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000188523412
,I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000188523427
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000170332081
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000170332090
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC0990019
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): le
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 170332003, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 188523324, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 188523335, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 188523412, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 188523427, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 170332081, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 170332090, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 188523436, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(44562740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(44562740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=84 entropy=72
D/wpa_supplicant( 1155): Add randomness: count=85 entropy=73
D/wpa_supplicant( 1155): Add randomness: count=86 entropy=74
D/wpa_supplicant( 1155): Add randomness: count=87 entropy=75
D/wpa_supplicant( 1155): Add randomness: count=88 entropy=76
D/wpa_supplicant( 1155): Add randomness: count=89 entropy=77
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ,ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=90 entropy=78
D/wpa_supplicant( 1155): Add randomness: count=91 entropy=79
D/wpa_supplicant( 1155): Add randomness: count=92 entropy=80
D/wpa_supplicant( 1155): Add randomness: count=93 entropy=81
D/wpa_supplicant( 1155): Add randomness: count=94 entropy=82
D/wpa_supplicant( 1155): Add randomness: count=95 entropy=83
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  906): getDiscoveryDongleList
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (813) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000170332003
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000206753736
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-77
I/wpa_supplicant( 1155): tsf=0000000188523335
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000206753767
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000206753757
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000206753777
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ####
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 170332003, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 206753736, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 188523335, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 206753767, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 206753757, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 206753777, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4491eb68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429a4500: PendingIntentRecord{42740f28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=211267, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4491eb68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=96 entropy=84
D/wpa_supplicant( 1155): Add randomness: count=97 entropy=85
D/wpa_supplicant( 1155): Add randomness: count=98 entropy=86
D/wpa_supplicant( 1155): Add randomness: count=99 entropy=87
D/wpa_supplicant( 1155): Add randomness: count=100 entropy=88
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan result,s from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=101 entropy=89
D/wpa_supplicant( 1155): Add randomness: count=102 entropy=90
D/wpa_supplicant( 1155): Add randomness: count=103 entropy=91
D/wpa_supplicant( 1155): Add randomness: count=104 entropy=92
D/wpa_supplicant( 1155): Add randomness: count=105 entropy=93
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (813) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000224982221
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000224982247
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-77
I/wpa_supplicant( 1155): tsf=0000000188523335
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos,
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000206753767
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000224982269
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
,I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000206753777
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 224982221, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 224982247, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 188523335, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 206753767, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 224982269, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 206753777, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43e1a688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4299f508: PendingIntentRecord{43bb4680 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229122, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{43a333f8: PendingIntentRecord{42f48f50 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452283764158, Int=1800000
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4736 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{424ef3c0: PendingIntentRecord{42c4cce8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452283810201, Int=10800000
,D/PMS     (  906): acquireWL(4443ebf8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(43e1a688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(42ef9b78): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1226 10028 null
,I/EventLogService( 1226): Aggregate from 1452283698722 (log), 1452281964099 (data)
D/PMS     (  906): releaseWL(4443ebf8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4736/10047)
,D/PMS     (  906): releaseWL(42ef9b78): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/Process (  906): killProcessQuiet, pid=4405
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4405:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4405
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  906): acquireWL(43c184f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{42c2a448: PendingIntentRecord{43bb4680 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=233009, Int=0
,D/PMS     (  906): releaseWL(43c184f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  906): acquireWL(4491c3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4491c3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=106 entropy=94
D/wpa_supplicant( 1155): Add randomness: count=107 entropy=95
D/wpa_supplicant( 1155): Add randomness: count=108 entropy=96
D/wpa_supplicant( 1155): Add randomness: count=109 entropy=97
D/wpa_supplicant( 1155): Add randomness: count=110 entropy=98
D/wpa_supplicant( 1155): Add randomness: count=111 entropy=99
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=112 entropy=100
D/wpa_supplicant( 1155): Add randomness: count=113 entropy=101
,D/wpa_supplicant( 1155): Add randomness: count=114 entropy=102
D/wpa_supplicant( 1155): Add randomness: count=115 entropy=103
D/wpa_supplicant( 1155): Add randomness: count=116 entropy=104
D/wpa_supplicant( 1155): Add randomness: count=117 entropy=105
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (813) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000243233391
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000243233417
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-77
I/wpa_supplicant( 1155): tsf=0000000243233429
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-84
I/wpa_supplicant( 1155): tsf=0000000206753767
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000243233450
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000243233459
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 243233391, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 243233417, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 243233429, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 206753767, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 243233450, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 243233459, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  906): acquireWL(43ef0090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43ef0090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=118 entropy=106
D/wpa_supplicant( 1155): Add randomness: count=119 entropy=107
D/wpa_supplicant( 1155): Add randomness: count=120 entropy=108
D/wpa_supplicant( 1155): Add randomness: count=121 entropy=109
D/wpa_supplicant( 1155): Add randomness: count=122 entropy=110
D/wpa_supplicant( 1155): Add randomness: count=123 entropy=111
D/wpa_supplicant( 1155): Add randomness: count=124 entropy=112
D/wpa_supplicant( 1155): Add randomness: count=125 entropy=113
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos,' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-92
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=126 entropy=114
D/wpa_supplicant( 1155): Add randomness: count=127 entropy=115
D/wpa_supplicant( 1155): Add randomness: count=128 entropy=116
D/wpa_supplicant( 1155): Add randomness: count=129 entropy=117
D/wpa_supplicant( 1155): Add randomness: count=130 entropy=118
D/wpa_supplicant( 1155): Add randomness: count=131 entropy=119
D/wpa_supplicant( 1155): Add randomness: count=132 entropy=120
D/wpa_supplicant( 1155): Add randomness: count=133 entropy=121
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
,I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1104) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000261463607
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000261463633
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000261463645
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-86
I/wpa_supplicant( 1155): tsf=0000000261463675
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000261463654
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000261463664
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000261463684
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC0990019
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=24
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 261463607, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 261463633, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 261463645, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 261463675, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 261463654, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 261463664, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 261463684, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 261463696, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-89], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-92], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/PMS     (  906): acquireWL(438b3520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429a4500: PendingIntentRecord{42740f28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=271266, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438b3520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=134 entropy=122
D/wpa_supplicant( 1155): Add randomness: count=135 entropy=123
D/wpa_supplicant( 1155): Add randomness: count=136 entropy=124
D/wpa_supplicant( 1155): Add randomness: count=137 entropy=125
D/wpa_supplicant( 1155): Add randomness: count=138 entropy=126
D/wpa_supplicant( 1155): Add randomness: count=139 entropy=127
D/wpa_supplicant( 1155): Add randomness: count=140 entropy=128
D/wpa_supplicant( 1155): Add randomness: count=141 entropy=129
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos,' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=142 entropy=130
D/wpa_supplicant( 1155): Add randomness: count=143 entropy=131
D/wpa_supplicant( 1155): Add randomness: count=144 entropy=132
D/wpa_supplicant( 1155): Add randomness: count=145 entropy=133
D/wpa_supplicant( 1155): Add randomness: count=146 entropy=134
D/wpa_supplicant( 1155): Add randomness: count=147 entropy=135
D/wpa_supplicant( 1155): Add randomness: count=148 entropy=136
D/wpa_supplicant( 1155): Add randomness: count=149 entropy=137
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (1104) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000279534174
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
,I/wpa_supplicant( 1155): tsf=0000000279534202
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000279534213
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-86
I/wpa_supplicant( 1155): tsf=0000000279534254
,I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000279534234
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
,I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000279534243
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000279534223
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC0990019
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=24,
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 279534174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 279534202, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 279534213, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 279534254, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 279534234, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 279534243, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 279534223, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 279534263, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-92], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43ad3c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43ad3c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=150 entropy=138
D/wpa_supplicant( 1155): Add randomness: count=151 entropy=139
D/wpa_supplicant( 1155): Add randomness: count=152 entropy=140
D/wpa_supplicant( 1155): Add randomness: count=153 entropy=141
D/wpa_supplicant( 1155): Add randomness: count=154 entropy=142
D/wpa_supplicant( 1155): Add randomness: count=155 entropy=143
D/wpa_supplicant( 1155): Add randomness: count=156 entropy=144
D/wpa_supplicant( 1155): Add randomness: count=157 entropy=145
D/wpa_supplicant( 1155): Add randomness: count=158 entropy=146
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End prin,t parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 8: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86,
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] 06:7c:34:38:27:cc freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=159 entropy=147
D/wpa_supplicant( 1155): Add randomness: count=160 entropy=148
,D/wpa_supplicant( 1155): Add randomness: count=161 entropy=149
D/wpa_supplicant( 1155): Add randomness: count=162 entropy=150
D/wpa_supplicant( 1155): Add randomness: count=163 entropy=151
D/wpa_supplicant( 1155): Add randomness: count=164 entropy=152
D/wpa_supplicant( 1155): Add randomness: count=165 entropy=153
D/wpa_supplicant( 1155): Add randomness: count=166 entropy=154
D/wpa_supplicant( 1155): Add randomness: count=167 entropy=155
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1218) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000279534174
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000297572056
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000297572066
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-86
I/wpa_supplicant( 1155): tsf=0000000297572107
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
,I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-86
I/wpa_supplicant( 1155): tsf=0000000297572098
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000297572087
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
,I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000297572075
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC0990019
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1155): freq=24
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 279534174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 297572056, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 297572066, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 297572107, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -86, frequency: 2437, timestamp: 297572098, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 297572087, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 297572075, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 297572116, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 8: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 297572044, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-92], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/jxcore-log( 4443): --= Surplus to requirements =--
I/jxcore-log( 4443): 
I/jxcore-log( 4443): ****TEST TOOK:  ms ****
I/jxcore-log( 4443): 
,I/jxcore-log( 4443): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4443): 
,E/cutils-trace( 4761): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4761): ====startRecUseTime====
D/htc.customization.log.level( 4761):  is 
,W/CustomizationLogLevel( 4761): Level value is invalid, use default level 2
,D/CustomizationManager( 4761):  Read ACC file spent 0.098 (s)
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4761): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4761): Parsing tag category name = system
I/CustomizationCIDLoader( 4761): Parsing tag category name = application,
I/CustomizationCIDLoader( 4761): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4761): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4761): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4761): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4761): Parsing tag category name = Settings
D/CustomizationManager( 4761):  Read CID file spent 0.150 (s)
,D/CustomizationManager( 4761):  All configurations done spent 0.150 (s),
,W/HtcNativeFlag( 4761): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4761): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4761): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4761): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4761, uid=2000 user=0
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=4443
,I/ActivityManager(  906): Killing 4443:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906):   Force finishing activity ActivityRecord{42c12aa0 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  906): Copying FileAsset 0x6cb54630 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/PackageSettings(  906): Skipping PackageSetting{42af8d10 com.example.hello/10356} due to missing metadata
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1210): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4443 uid 10348
I/acms    ( 1879): Unregistering com.test.thalitest
,E/acms    ( 1879): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1571): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1571): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/GeofencerStateMachine( 1455): Ignoring removeGeofence because network location is disabled.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  906): WIN DEATH: Window{42c32ca8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  906): Client connection lost with reason: 4
,D/PMS     (  906): acquireWL(44857130): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1455 10028 null
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/PMS     (  906): releaseWL(44857130): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 13.524MB for 1821008-byte allocation
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/VoicemailCleanupService( 1298): Cleaning up data for package: com.test.thalitest
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsRemoved
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
,D/PackageBroadcastService( 1226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4776 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/MultiDex( 4776): install
,I/MultiDex( 4776): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  906): Delaying start of: ServiceRecord{448c4ec8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/MultiDex( 4776): loading existing secondary dex files
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
,I/MultiDex( 4776): load found 1 secondary dex files
,I/MultiDex( 4776): install done
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4793 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PeopleContactsSync( 1226): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1226, uid=10028, userID:0
,I/Icing   ( 1226): doRemovePackageData com.test.thalitest
D/PMS     (  906): acquireWL(42f32d70): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(42f32d70): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ProviderInstaller( 4776): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4793): install
,I/MultiDex( 4793): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4793): loading existing secondary dex files
,I/MultiDex( 4793): load found 1 secondary dex files
,I/MultiDex( 4793): install done
,I/ProviderInstaller( 4793): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,E/SQLiteLog( 1226): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 1226): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/app_state.db, handle = 0x64460bd0
,E/ClearPendingStateOp( 1226): Runtime exception while performing operation
E/ClearPendingStateOp( 1226): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/ClearPendingStateOp( 1226): 	at bxi.b(SourceFile:267)
E/ClearPendingStateOp( 1226): 	at bxi.delete(SourceFile:259)
E/ClearPendingStateOp( 1226): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1226): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1226): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1226): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1226): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1226): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,F/ClearPendingStateOp( 1226): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1226): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
F/ClearPendingStateOp( 1226): 	at bxi.b(SourceFile:267)
F/ClearPendingStateOp( 1226): 	at bxi.delete(SourceFile:259)
F/ClearPendingStateOp( 1226): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1226): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1226): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1226): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1226): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1226): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=4064
I/ActivityManager(  906): Killing 4064:com.google.android.gm/u0a107 (adj 15): empty #17
,E/SharedPreferencesImpl( 1210): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/DropBoxManagerService(  906): Can't write: system_app_wtf
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  906): Recipient 4064
,I/[PluginManager]RegisterService( 1417): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteLog( 1417): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
,E/SQLiteDBG( 1417): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca5b180
,W/[PluginManager]RegisterService( 1417): provider may killed!
W/[PluginManager]RegisterService( 1417): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1417): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1417): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1417): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1417): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1417): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1417): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1417): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1417): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1417): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1417): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1417): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1417): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1417): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1417): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1417): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2878): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4816 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/SQLiteLog( 2878): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2878): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63725158
,W/dalvikvm( 2878): threadid=17: thread exiting with uncaught exception (group=0x41fc7e30)
,E/SQLiteDatabase( 4776): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4776): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4776): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4776): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4776): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4776): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4776): 	at ctn.run(SourceFile:985)
,W/dalvikvm( 4776): threadid=12: thread exiting with uncaught exception (group=0x41fc7e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2878): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2878): Process: com.google.android.googlequicksearchbox:search, PID: 2878
E/AndroidRuntime( 2878): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2878): 	at cid.d(PG:186)
E/AndroidRuntime( 2878): 	at clo.g(PG:594)
E/AndroidRuntime( 2878): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2878): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2878): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2878): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2878): 	at clr.tL(PG:827)
E/AndroidRuntime( 2878): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2878): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2878): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2878): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2878): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2878): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4776): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4776): Process: com.google.android.gms.drive, PID: 4776
E/AndroidRuntime( 4776): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4776): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4776): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4776): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4776): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4776): 	at ctn.run(SourceFile:985)
,E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
,D/Process ( 2878): killProcess, pid=2878
,D/Process ( 4776): killProcess, pid=4776
,D/Process ( 4776): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/Process ( 2878): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  906): Recipient 4776
,I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4776) has died.
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Recipient 2878
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2878) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
,D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2878): Died!
,E/SQLiteDatabase( 4816): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4816): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4816): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4816): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4816): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4816): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4816): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4816): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4816): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4816): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4816): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4816): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4816): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4816): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4816): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4816): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4816): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4816): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4816): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4816): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4816): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4816): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4816): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4816): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4816): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4816): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
,E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206),
E/SQLiteOpenHelper( 4816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188),
E/SQLiteOpenHelper( 4816): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4816): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4816): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4816): 	at aGL.a(GellyInjectorStoreBase.java:136),
E/SQLiteOpenHelper( 4816): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4816): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4816): 	,at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4816): ,	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4816): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4816): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4816): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4816): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4816): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4816): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4816): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4816): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4816): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4816): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4816): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4816): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4816): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4816): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4816): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4816): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4816): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4816): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4816): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4816): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4816): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4816): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4816): threadid=11: thread exiting with uncaught exception (group=0x41fc7e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs,
E/AndroidRuntime( 4816): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4816): Process: com.google.android.apps.docs, PID: 4816
E/AndroidRuntime( 4816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4816): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4816): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4816): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4816): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4816): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  906): Can't write: system_app_crash
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
,E/SQLiteDatabase( 4816): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4816): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4816): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4816): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4816): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4816): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4816): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4816): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4816): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4816): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4816): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4816): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4816): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4816): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4816): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4816): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4816): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4816): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4816): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4816): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4816): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4816): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4816): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4816): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4816): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4816): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4816): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4816): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4816): killProcess, pid=4816
W/SQLiteOpenHelper( 4816): Opened ClientFlag.db in read-only mode
,D/Process ( 4816): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 ,
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4834 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Recipient 4816
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=4320
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4320:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4816) has died.
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4320
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@4248add0 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,W/ContextImpl( 4834): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4847 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4834): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
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
,W/dalvikvm( 4834): threadid=10: thread exiting with uncaught exception (group=0x41fc7e30)
,E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4834): FATAL EXCEPTION: IntentService[KeyChainService]
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
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4834): killProcess, pid=4834
,D/Process ( 4834): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,W/PackageManager(  906): Unable to load service info ResolveInfo{437fd850 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452283890568.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 4834
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4834) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10394ms
,D/AppTag  ( 4847): getInstance(Context context)
,D/AppTag  ( 4847): getInstance(Context context)
,D/AppTag  ( 4847): onCreate()
,D/PMS     (  906): acquireWL(4483aec8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4190 10160 null
,I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4864 uid=10098 gids={50098, 3003, 5012}
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 15.210MB for 1821008-byte allocation
D/PMS     (  906): releaseWL(4483aec8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 16.948MB for 1821008-byte allocation
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,I/DeviceManagement( 4864): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4864 dbg=false s=true
,I/DeviceManagement( 4864): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,D/RemoteDisplayProvider(  906): start
I/DeviceManagement( 4864): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4864): WorkflowService: Starting workflow service
I/DeviceManagement( 4864): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@4242c420] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4864): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4864): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4864): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4864): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4864): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4864): SessionStateController: Checking invariants...
I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4881 uid=10099 gids={50099, 3003, 5012}

```
