#### Test 54970261ac9928f_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
E/cutils-trace( 4383): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4383): ====startRecUseTime====
D/htc.customization.log.level( 4383):  is 
W/CustomizationLogLevel( 4383): Level value is invalid, use default level 2
D/CustomizationManager( 4383):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 4383): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4383): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4383): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4383): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4383): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4383): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4383): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4383): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4383): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4383): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4383): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4383): Parsing tag category name = system
I/CustomizationCIDLoader( 4383): Parsing tag category name = application
I/CustomizationCIDLoader( 4383): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4383): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4383): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4383): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4383): Parsing tag category name = Settings
D/CustomizationManager( 4383):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4383):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 4383): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4383): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4383): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4383): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4383
D/PMS     (  910): acquireHCC(42ca05c0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(428d8cb0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1134507944
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4208d078
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  910): acquireWL(42956568): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4394 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4394): Binding Chromium to main looper Looper (main, tid 1) {41eded58}
I/LibraryLoader( 4394): Expected native library version number "",actual native library version number ""
I/chromium( 4394): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4394): Initializing chromium process, renderers=0
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424da7b8:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4394): 1106202592: getState(). Returning 12
D/PMS     (  910): acquireWL(429dcb48): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  910): acquireWL(42908940): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  910): releaseWL(42908940): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4394): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4394): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4394): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4394): Local Branch: 
I/Adreno-EGL( 4394): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4394): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4394):                  aa63bbd948f41d15fc72f585e
W/chromium( 4394): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4394): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4394): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4394): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4394): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4394): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4394): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4394): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4394): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4394): CordovaWebView is running on device made by: HTC
,W/AwContents( 4394): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  910): Disable input method client, pid=1272
W/ResourceType( 4394): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4394): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41f26690, mServedView=org.apache.cordova.engine.SystemWebView{41eec2f8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  910): Enable input method client, pid=4394
,W/AwContents( 4394): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +266ms
,D/PMS     (  910): releaseWL(42956568): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{444c9140 u0 com.htc.htclocationservice/.AutoSettingService}
,D/JsMessageQueue( 4394): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4394): JniHelper::setJavaVM(0x41a9d010), pthread_self() = 1662817152
,D/JX-Cordova( 4394): jxcore cordova android initializing
,I/dalvikvm-heap( 4394): Grow heap (frag case) to 11.581MB for 95956-byte allocation
,I/dalvikvm-heap( 4394): Grow heap (frag case) to 11.660MB for 143930-byte allocation
,I/dalvikvm-heap( 4394): Grow heap (frag case) to 11.775MB for 215890-byte allocation
,I/dalvikvm-heap( 4394): Grow heap (frag case) to 11.950MB for 323830-byte allocation
,I/SensorManager(  910): mEventCount = 1051
,I/dalvikvm-heap( 4394): Grow heap (frag case) to 12.222MB for 485740-byte allocation
,I/dalvikvm-heap( 4394): Grow heap (frag case) to 13.222MB for 1092904-byte allocation
,I/dalvikvm-heap( 4394): Grow heap (frag case) to 14.093MB for 1639352-byte allocation
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4394): Grow heap (frag case) to 15.448MB for 2459024-byte allocation
,I/dalvikvm-heap( 4394): Grow heap (frag case) to 17.464MB for 3688532-byte allocation
,W/jxcore-log( 4394): Initializing JXcore engine
,W/jxcore-log( 4394): JXcore engine is ready
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
,D/PMS     (  910): releaseHCC(42ca05c0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(428d8cb0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4394): Starting JXcore engine
D/PMS     (  910): acquireWL(4267eef8): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
,D/PMS     (  910): releaseWL(4267eef8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(42261f50): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
,D/PMS     (  910): releaseWL(42261f50): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(42800ce0): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
,D/PMS     (  910): releaseWL(42800ce0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/jxcore-log( 4394): Platform android
W/jxcore-log( 4394): 
,W/jxcore-log( 4394): Process ARCH arm
W/jxcore-log( 4394): 
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
,I/ActivityManager(  910): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4441 uid=10077 gids={50077}
,D/PMS     (  910): acquireWL(42a33ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10077}
,V/AlarmManager(  910): sending alarm PendingIntent{4276ffc0: PendingIntentRecord{421534d8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452269559761, Int=60000
,D/PMS     (  910): releaseWL(42a33ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4441): SMSBackupAgentService started
,D/SMSBackup( 4441): Checking restore status
D/SMSBackup( 4441): Restore complete
,D/SMSBackup( 4441): cancelCheckAlarm
,D/SMSBackup( 4441): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  910): killProcessQuiet, pid=3091
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3091:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3091
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 4394): JXcore Cordova bridge is ready!
I/jxcore-log( 4394): 
,W/jxcore-log( 4394): JXcore engine is started
,I/chromium( 4394): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4394): Toggling radios to true
I/jxcore-log( 4394): 
,D/BluetoothAdapter( 4394): enable(): BT is already enabled..!
,D/WifiManager( 4394): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 921
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
,W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
W/Settings:Agent(  910): << traceCallingStack(): 1(ms),
D/WifiManager( 4394): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/WifiManager( 4394): reconnect: Base Package Name=com.test.thalitest, uid=10348
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): TDLS: Tear down peers
,I/wpa_supplicant( 1162): wpa_driver_nl80211_disconnect(reason_code=3),
,I/jxcore-log( 4394): Radios toggled,
I/jxcore-log( 4394): 
D/WifiService(  910): setWifiEnabled: true pid=4394, uid=10348
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiService(  910): New client listening to asynchronous messages
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1162): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1162): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1162): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb72f5bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1162): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1162): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
,D/wpa_supplicant( 1162): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  910):    returned true
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  910):    returned true
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(429c8fd8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: RECONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): Fast associate: Old scan results
I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0(  910):    returned true
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19534 mDataStallAlarmIntent=PendingIntent{42145628: PendingIntentRecord{428d5260 android broadcastIntent}}
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
D/WifiNative-wlan0(  910):    returned true
,D/UsbnetStateTracker(  910): isAvailable+-
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4171): >>>>>WISPrService start isConnected = false<<<<<
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WISPrService( 4171): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiService(  910): New client listening to asynchronous messages
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/PMS     (  910): acquireWL(429a1490): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/libc    (  357): [NET] entry_id:5   entry:0xb7198818  removed 
D/libc    (  357): [NET] entry_id:6   entry:0xb71986f0  removed 
D/libc    (  357): [NET] entry_id:4   entry:0xb7197fd8  removed 
D/libc    (  357): [NET] entry_id:2   entry:0xb7198108  removed 
D/libc    (  357): [NET] entry_id:7   entry:0xb71981d0  removed 
D/libc    (  357): [NET] entry_id:3   entry:0xb71982e0  removed 
D/libc    (  357): [NET] entry_id:1   entry:0xb7198410  removed 
D/libc    (  357): [NET] entry_id:8   entry:0xb7197d90  removed 
,D/libc    (  357): *************************
D/libc    (  357): *** DNS CACHE FLUSHED ***
D/libc    (  357): *************************
,D/WISPrService( 4171): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4171): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  910): acquireWL(43c48698): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/PMS     (  910): acquireWL(439d4218): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
I//system/bin/ip(  357): RTNETLINK answers: No such process
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/logwrapper(  357): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SCAN
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/PMS     (  910): releaseWL(43c48698): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1368/10028)
D/BatSI   (  910): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  910): releaseWL(429a1490): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/WifiNative-wlan0(  910):    returned false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/PMS     (  910): releaseWL(439d4218): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  910): releaseWL(429dcb48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/NetworkMonitor( 3884): type=WIFI subType= reason=null isConnected=false
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  910): NoActiveNetworkState
,I/Tethering(  910): ipv4Default null
,I/Tethering(  910): No IPv4 upstream interface, giving up.
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1921/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (3884/10154)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(435d7898): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1434/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4284/10100)
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4284/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2430/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4464 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4464): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4464): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4464): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  910): releaseWL(435d7898): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/SystemClassLoaderAdder( 4464): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4464): Preparing secondary program dexes.
V/DexLibLoader( 4464): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4464): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4464): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4464): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4464): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4464): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4464): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4464): Dex already copied
D/OdexVerifier( 4464): Odex verification is skipped.
,V/DexLibLoader( 4464): Creating class loader
V/DexLibLoader( 4464): Finished creating class loader
V/DexLibLoader( 4464): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4464): Dex already copied
D/OdexVerifier( 4464): Odex verification is skipped.
,V/DexLibLoader( 4464): Creating class loader
,V/DexLibLoader( 4464): Finished creating class loader
V/DexLibLoader( 4464): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4464): Dex already copied
D/OdexVerifier( 4464): Odex verification is skipped.
,V/DexLibLoader( 4464): Creating class loader,
V/DexLibLoader( 4464): Finished creating class loader
V/DexLibLoader( 4464): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4464): Dex already copied
D/OdexVerifier( 4464): Odex verification is skipped.
,V/DexLibLoader( 4464): Creating class loader
,V/DexLibLoader( 4464): Finished creating class loader
,V/DexLibLoader( 4464): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4464): DexLibLoader.ensureDexLoaded took 18 ms
,W/dalvikvm( 4464): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1162): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-76
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1162): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1162): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1162): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=9 entropy=0
D/wpa_supplicant( 1162): Add randomness: count=10 entropy=1
D/wpa_supplicant( 1162): Add randomness: count=11 entropy=2
D/wpa_supplicant( 1162): Add randomness: count=12 entropy=3
D/wpa_supplicant( 1162): Add randomness: count=13 entropy=4
D/wpa_supplicant( 1162): Add randomness: count=14 entropy=5
D/wpa_supplicant( 1162): Add randomness: count=15 entropy=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
I/wpa_supplicant( 1162): Start print parameters
I/w,pa_supplicant( 1162): wpa_s->wpa_state is 3
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 1
I/wpa_supplicant( 1162): wpa_s->is_screen_on 1
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): selected network = 1
D/wpa_supplicant( 1162): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb72f74e8  current_ssid=0x0
D/wpa_supplicant( 1162): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1162): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1162): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1162): check if in concurrent case
,I/wpa_supplicant( 1162): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1162): RSN: PMKSA cache search - network_ctx=0xb72f74e8 try_opportunistic=0
D/wpa_supplicant( 1162): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1162): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1162): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1162): nl80211: Unsubscribe mgmt frames handle 0xb72f6718 (mode change)
D/wpa_supplicant( 1162): nl80211: Subscribe to mgmt frames with non-AP handle 0xb72f6718
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb72f6718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb72f6718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb72f6718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb72f6718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb72f6718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb72f6718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb72f6718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb72f6718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb72f6718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb72f6718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1162):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162):   * freq=2412
,D/wpa_supplicant( 1162):   * Auth Type 0
D/wpa_supplicant( 1162):   * WPA Versions 0x2
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1162): nl80211: Connect request send successfully
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  910): doString: LIST_DONGLES
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,D/WirelessDisplayService(  910): getDiscoveryDongleList
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1162): reply (921) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-47
I/wpa_supplicant( 1162): tsf=0000000106331243
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-53
I/wpa_supplicant( 1162): tsf=0000000106331259
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=2
I/wpa_supplicant( 1162): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-76
I/wpa_supplicant( 1162): tsf=0000000106331268
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1162): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-77
I/wpa_supplicant( 1162): tsf=0000000106331264
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-84
I/wpa_supplicant( 1162): tsf=0000000106331272
I/wpa_supplicant( 1162): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=UPC Wi-Free
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=5
I/wpa_supplicant( 1162): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-85
I/wpa_supplicant( 1162): tsf=0000000106331276
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC5999698
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=6
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-53
I/wpa_supplicant( 1162): tsf=0000000106331254
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ####
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 106331243, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 106331259, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -76, frequency: 2437, timestamp: 106331268, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 106331264, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 106331272, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabili,ties: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 106331276, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 106331254, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 7 to mScanResults
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (7) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/BatSI   (  910): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,W/dalvikvm( 4464): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1162): nl80211: Connect event
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1162): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Add randomness: count=16 entropy=7
I/wpa_supplicant( 1162): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): TDLS: Remove peers on association
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1162): EAPOL: enable timer tick
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1162): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1162): Get randomness: len=32 entropy=8
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb72f69f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f94b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1162):    broadcast key
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
D/WifiStateMachine(  910): This record is existed, only update it...
I/wpa_supplicant( 1162): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1162): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1162): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1162): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1162): set send_ind_to_ndc = 0
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1162): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1162): EAPOL authentication completed successfully
I/wpa_supplicant( 1162): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED,
,E/FbInjectorInitializer( 4464): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.,
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...,
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WISPrService( 4171): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4171): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 1
,I/wpa_supplicant( 1162): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(43ae49b0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@428aead0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@428aead0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4464): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4464): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4464): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=3851
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 3851:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  910): acquireWL(43e9cb88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1231 10028 null
,D/PMS     (  910): acquireWL(42945148): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1231 10028 null
,D/PMS     (  910): releaseWL(43e9cb88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1231/10028)
,D/GCM     ( 1368): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1231/10028)
,D/PMS     (  910): releaseWL(42945148): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1412): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Recipient 3851
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4493 uid=10078 gids={50078, 3003, 5012}
,D/AutoSetting( 1412): Util - no network available!
,D/AutoSetting( 1412): service - onCreate()
,D/AutoSetting( 1412): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
,D/AutoSetting( 1412): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  910): request 4285e260 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1412): service - mHandler: cancel location update
,D/AutoSetting( 1412): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4464): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4464): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4464): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4493): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4493): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4493): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4493): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4529 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4493/10078)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4493/10078)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4464): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4493/10078)
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/Process (  910): killProcessQuiet, pid=4226
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4546 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  910): Killing 4226:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4226
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 9.958MB for 84664-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4546): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4546): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
I/dalvikvm-heap( 4464): Grow heap (frag case) to 9.976MB for 28144-byte allocation
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
E/dalvikvm( 4464): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4464): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
E/dalvikvm( 4464): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4464): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/dalvikvm( 4464): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4464): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4464): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4464): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4464): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4464): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4464): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4464): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4464): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4464): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/dalvikvm( 4464): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/GAV2    ( 4546): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/dalvikvm( 4464): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/dalvikvm( 4464): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4464): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/ContextImpl( 4546): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  910): releaseWL(43ae49b0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4546): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED -1 -> 3
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1162): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
,D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -53, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19536 delay=15s
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiWatchdogStateMachine(  910): WAN detection
D/WISPrService( 4171): >>>>>WISPrService start isConnected = true<<<<<
I/dalvikvm-heap( 4464): Grow heap (frag case) to 10.041MB for 39954-byte allocation
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1120): WifiActivity: 1
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/MDST    (  910): default: setTeardownRequested(true)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@4280ecb0
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    (  357): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 10.118MB for 79892-byte allocation
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  910): acquireWL(43bedd40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4493/10078)
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
I/QuickSettingWifi( 1120): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(42e503d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1231 10028 null
D/PMS     (  910): releaseWL(43bedd40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  910): acquireWL(4373f420): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1231 10028 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(42e503d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I//system/bin/ip(  357): RTNETLINK answers: No such file or directory
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1231/10028)
I/logwrapper(  357): /system/bin/ip terminated by exit(254)
I/CheckinService( 1231): Preparing to send checkin request
I/EventLogService( 1231): Accumulating logs since 1452269512450
,I//system/bin/ip(  357): RTNETLINK answers: No such process
,I/logwrapper(  357): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1231): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1231): Using GMS GoogleHttpClient
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4546/10151)
,V/WebViewChromiumFactoryProvider( 4546): Binding Chromium to main looper Looper (main, tid 1) {41ee42f0}
,I/LibraryLoader( 4546): Expected native library version number "",actual native library version number ""
,I/chromium( 4546): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4546): Initializing chromium process, renderers=0
D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,E/AudioManagerAndroid( 4546): BLUETOOTH permission is missing!
D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (1231/10028)
D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.google.android.gms (1231/10028)
D/PMS     (  910): acquireWL(428d2a88): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  910): acquireWL(429f5710): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  910): releaseWL(428d2a88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4546): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4546): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4546): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4546): Local Branch: 
I/Adreno-EGL( 4546): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4546): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4546):                  aa63bbd948f41d15fc72f585e
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,I/NSApplication( 4546): Starting up...
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4546/10151)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4546/10151)
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ccf3c8 u0 ReceiverList{438f6938 4464 com.facebook.katana/10026/u0 remote:4305b240}}
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ccf3c8 u0 ReceiverList{438f6938 4464 com.facebook.katana/10026/u0 remote:4305b240}}
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44391e48 u0 ReceiverList{44391d88 4464 com.facebook.katana/10026/u0 remote:43cb8158}}
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1231): awaiting user notification for token
,I/RemoteViews( 1120): com.google.android.gms (false,0)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{420282b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
I/RemoteViews.Performance( 1120): com.google.android.gms 1 11 2 12
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4149/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4149/10160)
,I/ActivityManager(  910): Killing 4003:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4003
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
,D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
,D/wpa_supplicant( 1162): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1162): EAPOL: disable timer tick
,D/PMS     (  910): acquireWL(447d80b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
,D/PMS     (  910): acquireWL(44798690): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4599 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCoreFlp( 1434): Unknown pending intent to remove.
D/PMS     (  910): releaseWL(447d80b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  910): releaseWL(44798690): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
,I/ActivityManager(  910): Recipient 4003
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4464): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/MultiDex( 4599): install
I/MultiDex( 4599): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4464): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/MultiDex( 4599): loading existing secondary dex files
I/MultiDex( 4599): load found 1 secondary dex files
I/MultiDex( 4599): install done
,I/ProviderInstaller( 4599): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4599): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4599): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4599): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4599): Local Branch: 
I/Adreno-EGL( 4599): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4599): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4599):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4599): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4599): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4599): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4599): Local Branch: 
I/Adreno-EGL( 4599): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4599): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4599):                  aa63bbd948f41d15fc72f585e
D/WIFI_ICON( 1120): WifiActivity: 2
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  910): releaseWL(429c8fd8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 3884): type=WIFI subType= reason=null isConnected=true
I/acms    ( 1921): Checking Certificates
I/acms    ( 1921): Checking Developer Certificates
I/acms    ( 1921): Checking Application Certificates
I/acms    ( 1921): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1921): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
,I/acms    ( 1921): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1921): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1921): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
D/CaptivePortalTracker(  910): NoActiveNetworkState
I/acms    ( 1921): Updating next query delay: 75600000
I/mlserverapp( 1921): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1921): cancelACMSProgrammedChecks
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4284/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1921/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1434/10028)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (3884/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4493/10078)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3914/10051)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4284/10100)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
D/PMS     (  910): acquireWL(428c7de0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(443d84a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
D/PMS     (  910): releaseWL(443d84a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(428c7de0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2430/10021)
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(42466360): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1231 10028 null
,D/PMS     (  910): releaseWL(42466360): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1368): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): acquireWL(42866c98): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1368 10028 null
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1368): [NET] getaddrinfo-, 1
,D/libc    ( 1368): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =4f03 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/AutoSetting( 1412): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1231/10028)
,D/MobileConnectivityChangeReceiver( 4493): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4493): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1412): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1412): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1412): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1412): service - onStartCommand() REMOVE current location bundle
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4546/10151)
,D/AutoSetting( 1412): service - handleMessage() setting current location null
D/AutoSetting( 1412): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1412): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4149/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4149/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 187
D/libc    (  357): [NET]res_nsend:resplen=79
D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1368): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4149): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): acquireWL(429d9b78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/PMS     (  910): releaseWL(429d9b78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4599): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/GCM     ( 1368): Connected
D/PMS     (  910): acquireWL(42423f10): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): releaseWL(42866c98): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
,I/Adreno-EGL( 4599): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4599): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4599): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4599): Local Branch: 
I/Adreno-EGL( 4599): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4599): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4599):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): releaseWL(42423f10): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  910): acquireWL(443c4e50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
,D/GCM     ( 1368): Message class mpf
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): acquireWL(4255ca08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/PMS     (  910): releaseWL(443c4e50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4599/10028)
D/PMS     (  910): releaseWL(4255ca08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/CheckinTask( 1231): Sending checkin request (8973 bytes)
D/libc    ( 1231): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1231): [NET] getaddrinfo-,err=8
D/libc    ( 1231): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1231): [NET] getaddrinfo-, 1
,D/libc    ( 1231): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =7280 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 17
D/libc    (  357): [NET]res_nsend:resplen=84
,D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1231): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1231): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4,
,D/libc    ( 1231): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=9 [21][2][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1120): WifiActivity: 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  910): acquireWL(43188600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/PMS     (  910): releaseWL(43188600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (1231/10028)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.google.android.gms (1231/10028)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [3][0][0]
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1231): awaiting user notification for token
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{4202a838 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 7 2 12
,I/CheckinTask( 1231): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1231): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1231/10028)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1231/10028)
,D/PMS     (  910): releaseWL(4373f420): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 1231): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ffcb80 that was originally bound here
E/ActivityThread( 1231): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ffcb80 that was originally bound here
E/ActivityThread( 1231): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1231): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1231): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1231): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1231): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1231): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1231): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1231): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1231): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1231): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1231): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1231): 	at bks.a(SourceFile:298)
E/ActivityThread( 1231): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1231): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1231): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1368): GCM config loaded
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  910): BroadcastRSSIForIMS, newrssi =-54 , oldRssi= -200
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,W/fb4a(:<default>):UserScope( 4464): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4464): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,E/fb4a(:<default>):LocalFbBroadcastManager( 4464): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =a9cc +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  357): [NET]res_nsend:resplen=172
,D/libc    (  357): [NET]res_queryN: exit 3, ancount=4
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/104.81.130.175
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  910): releaseWL(429f5710): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42543ad0
,W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42543ad0, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427494e0
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@42a42078
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 370ms
D/NfcService( 1258): ScreenObserver: OFF
D/NfcService( 1258): applyRouting - 0
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@439d9c78)
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
I/InputMethodManagerService(  910): Disable input method client, pid=4394
D/PMN     (  910): wakingUp
D/NfcService( 1258): applyRouting -2
,I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  910): acquireWL(4315a950): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  910): releaseWL(4315a950): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  910): No lock screen! windowToken=null
,D/PMN     (  910): onScreenOn
,D/MtpService( 2430): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2430): [MTP][onReceive]-
,D/NfcService( 1258): applyRouting - 0
,D/AutoSetting( 1412): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  910): acquireWL(443ea850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(443ea850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43c7cb68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
,D/NfcService( 1258): applyRouting -2
,D/AutoSetting( 1412): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  910): releaseWL(43c7cb68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/TetherSettings( 4171): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4171): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 4171): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 4171): Cust_ConnectToPC   : spcsc>false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/        ( 4171): Cust_ConnectToPC   : IPT>true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19537 delay=15s
,D/        ( 4171): Cust_ConnectToPC   : Singel_USB>false
,I/ClockThread( 1120): stop update clock
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
W/Settings( 4171): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:On
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/SmartNS_Utility( 4171): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4171): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4171): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,D/WIFI_ICON( 1120): WifiActivity: 2
I/PSReceiver( 4171): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,I/SmartNS_PSService( 4171): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4171): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4171):  defaultType:0
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,V/SRS_Proc(  364): ParamSet string: screen_state=on
W/ContextImpl( 4171): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/NetworkPolicy(  910): updateScreenOn: false
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4649 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1848): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1848): onScreenOn: 1452269567384
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1848): onScreenOn: 1452269567384
D/PMS     (  910): acquireWL(43c36cc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
D/PMS     (  910): releaseWL(43c36cc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/ContextImpl( 4649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427494e0
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427494e0, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@42a42078
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  910): goingToSleep
D/PMS     (  910): acquireWL(433b2d38): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,D/PMS     (  910): acquireWL(43ed1b70): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4649 1000 null
,D/SmartSyncUtils( 4649): isEpsOn(), nState = 0
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19537 mDataStallAlarmIntent=PendingIntent{43ae4dc8: PendingIntentRecord{428d5260 android broadcastIntent}}
D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:Off
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1162): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  364): ParamSet string: screen_state=off
D/PMS     (  910): acquireWL(438f4cb8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
D/PMS     (  910): releaseWL(43ed1b70): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/NetworkPolicy(  910): updateScreenOn: false
,D/SmartSyncUtils( 4649): getMobilePolicyEnabled, result = true
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/Process (  910): killProcessQuiet, pid=4254
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  910): releaseWL(438f4cb8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  910): Killing 4254:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4254
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4649): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4649): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4649): isEpsOn(), nState = 0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiService(  910): New client listening to asynchronous messages
,D/ContactMessageStore( 1247): start background delete task...
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] getTotalRam: 1873 Mb
D/PMS     (  910): acquireWL(42a966f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
D/PMS     (  910): releaseWL(42a966f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1848): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1848): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1848): disableBatteryAlarm
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a42078
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1848): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1848): onScreenOff
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a42078, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a42078, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a42078
,D/AutoSetting( 1412): service - mHandler: cancel location update
,D/AutoSetting( 1412): service -           changes count: 0
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42a45e30 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42a45e30 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  910): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  910): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  910): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  910): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  910): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  910): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  910): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  910): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  910): Activity pause timeout for ActivityRecord{4214e5c0 u0 com.test.thalitest/.MainActivity t2}
,I/GAV2    ( 4546): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  910): acquireWL(42d6b938): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
,D/PMS     (  910): acquireWL(4299ba68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
,D/PMS     (  910): releaseWL(42d6b938): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  910): releaseWL(4299ba68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC <<
,I/jxcore-log( 4394): Test app app.js loaded
I/jxcore-log( 4394): 
,I/Choreographer( 4394): Skipped 536 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4394): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4394): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41eec2f8 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  910): releaseWL(433b2d38): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4394): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Process (  910): killProcessQuiet, pid=4284
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4284:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4284
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1520): service - handleMessage() stop self
,D/AutoSetting( 1520): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=4308
,D/AutoSetting( 1520): service - handleMessage() quit looper
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4308:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4308
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 10.986MB for 41506-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 11.018MB for 62254-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 11.024MB for 47940-byte allocation
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 11.078MB for 72932-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 11.084MB for 49180-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 11.122MB for 64750-byte allocation
,D/libc    ( 4464): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4464): [NET] getaddrinfo-,err=8
D/libc    ( 4464): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4464): [NET] getaddrinfo-, 1
,D/libc    ( 4464): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =2145 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 52
D/libc    (  357): [NET]res_nsend:resplen=93
D/libc    (  357): [NET]res_queryN: exit 3, ancount=3
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4464): [NET] getaddrinfo_proxy-, success
I/global  ( 4464): call createSocket() return a new socket.
D/libc    ( 4464): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4464): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4464): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4464): [NET] getaddrinfo-,err=8
,D/PMS     (  910): acquireWL(439036b0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4464 10026 null
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4464): I/O error closing connection
I/global  ( 4464): java.net.SocketException: Socket is closed
I/global  ( 4464): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4464): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4464): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4464): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4464): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4464): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4464): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4464): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4464): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4464): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4464): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4464): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4464): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4464): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4464): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4464): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4464): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4464): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4464): Removing a connection that never existed!
D/PMS     (  910): releaseWL(439036b0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43212c80 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(43821ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=124239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43821ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43f9abe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43f9abe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1412): service - mHandler: update timezone
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1520): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1616): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1520): service - mHandler: update timezone
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1520): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1520): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1120): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{42261010 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.htclocationservice 2 7 3 11
,D/PMS     (  910): acquireWL(43b54de0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{427a96d0: PendingIntentRecord{42376840 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141153, Int=0
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  910): sending alarm PendingIntent{429b8bb0: PendingIntentRecord{428130f8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141755, Int=0
D/PMS     (  910): acquireWL(42e31ee8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): releaseWL(43b54de0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  910): acquireWL(4445ae68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/PMS     (  910): releaseWL(4445ae68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =741 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE,
,D/AutoSetting( 1412): service - handleMessage() stop self
,D/AutoSetting( 1412): service - handleMessage() quit looper
,D/AutoSetting( 1412): service - onDestroy() END
D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 30
D/libc    (  357): [NET]res_nsend:resplen=238
,D/libc    (  357): [NET]res_queryN: exit 3, ancount=10
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(42e31ee8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  910): killProcessQuiet, pid=3914
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3914:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3914
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{42923f30 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1520): service - handleMessage() stop self
,D/AutoSetting( 1520): service - onDestroy() END
,D/AutoSetting( 1520): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4271,
,I/ActivityManager(  910): Killing 4271:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4271
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(44476cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(44476cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(43fab158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=184239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43fab158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43ed4310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43ed4310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(43a047d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{42630398: PendingIntentRecord{43c905b0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227399, Int=0
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4689 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  910): sending alarm PendingIntent{428b0968: PendingIntentRecord{42771810 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452269675681, Int=10800000
,D/PMS     (  910): releaseWL(43a047d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4689/10047),
,D/Process (  910): killProcessQuiet, pid=4326
,I/ActivityManager(  910): Killing 4326:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4326
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1231/10028)
,D/PMS     (  910): acquireWL(43519770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{43857170: PendingIntentRecord{43c905b0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231651, Int=0
,D/PMS     (  910): releaseWL(43519770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  910): acquireWL(43261d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43261d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(428e1d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=244239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(428e1d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4286b4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(4286b4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(41f0cc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(41f0cc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(429cd550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=304238, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(429cd550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(427c8120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(427c8120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4394): TAP version 13
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # multiplex can send data
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 1 String should be length:200
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup,
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # basic
I/jxcore-log( 4394): 
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(428065a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(428065a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 2 sane
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # another
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4394): ok 3 sane
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 4 should be equal
I/jxcore-log( 4394): 
,D/PMS     (  910): acquireWL(4299f9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/jxcore-log( 4394): ok 5 null
I/jxcore-log( 4394): 
V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=364239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/jxcore-log( 4394): ok 6 (unnamed assert)
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 7 should be equal
I/jxcore-log( 4394): 
D/PMS     (  910): releaseWL(4299f9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4394): ok 8 should not throw
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4394): 
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1368): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1368): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1368): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/PlayEventLogger( 4113): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4113): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4113): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4113): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4113): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4113): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4113): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4113): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41f6e910 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 5 13 4 12
,D/libc    ( 4113): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4113): [NET] getaddrinfo-,err=8
D/libc    ( 4113): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4113): [NET] getaddrinfo-, 1
,D/libc    ( 4113): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =d06d +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  357): [NET]res_nsend:resplen=87
,D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4113): [NET] getaddrinfo_proxy-, success
I/global  ( 4113): call createSocket() return a new socket.
D/libc    ( 4113): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4113): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4113): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4113): [NET] getaddrinfo-,err=8
,D/PMS     (  910): acquireWL(429c1d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(429c1d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 9 (unnamed assert)
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 10 (unnamed assert)
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 11 should not throw
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 12 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 13 should be equal,
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup,
I/jxcore-log( 4394): 
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4394): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 14 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # failed to get mobile documents path
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 15 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 16 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 17 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 18 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #init should register the networkChanged event
I/jxcore-log( 4394): 
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 19 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #startBroadcasting should throw on null device name
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 20 should throw
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 21 should throw
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 22 should throw
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 23 should throw
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #startBroadcasting should throw on negative port
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 24 should throw
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #startBroadcasting should throw on too large port
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 25 should throw
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 26 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 27 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 28 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,D/PMS     (  910): acquireWL(429f3528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{4389fa30: PendingIntentRecord{43c21080 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=411405, Int=300000
,D/PMS     (  910): releaseWL(429f3528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,I/jxcore-log( 4394): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,D/PMS     (  910): acquireWL(428b6420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(428b6420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4394): ok 29 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 30 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 31 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4394): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4394): 
,D/PMS     (  910): acquireWL(43ce6d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=424238, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43ce6d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 32 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 33 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4394): 
,D/PMS     (  910): acquireWL(429798f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(429798f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 34 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 35 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 36 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 37 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 38 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 39 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 40 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 4394): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,D/PMS     (  910): acquireWL(428efdd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(428efdd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4394): ok 41 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 42 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4394): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,D/PMS     (  910): acquireWL(4278f478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=484239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4278f478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4394): ok 43 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): ok 44 should be equal
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # setup
I/jxcore-log( 4394): 
,I/jxcore-log( 4394): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4394): 
,D/PMS     (  910): acquireWL(424ed8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(424ed8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4394): # teardown
I/jxcore-log( 4394): 
,W/dalvikvm( 4394): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4394): threadid=1: thread exiting with uncaught exception (group=0x41aaee30)
,E/AndroidRuntime( 4394): FATAL EXCEPTION: main
E/AndroidRuntime( 4394): Process: com.test.thalitest, PID: 4394
E/AndroidRuntime( 4394): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4394): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4394): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4394): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4394): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4394): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 4394): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/AndroidRuntime( 4394): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4394): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4394): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4394): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4394): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4394): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4394): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4394): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4394): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4394): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4394): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4394): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  910): App crashed! Process: com.test.thalitest
W/ActivityManager(  910):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  910): killProcessQuiet, pid=4343
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,I/ActivityManager(  910): Killing 4343:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process ( 4394): killProcess, pid=4394
D/Process ( 4394): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  910): Recipient 4343
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1212): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 4394 uid 10348
,I/ActivityManager(  910): Recipient 4394
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  910): WIN DEATH: Window{427d6360 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  910): Process com.test.thalitest (pid 4394) has died.
,D/WifiService(  910): Client connection lost with reason: 4
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(428ee6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(428ee6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  404): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  910): acquireWL(43c376c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=544238, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43c376c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(428eaa88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(428eaa88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43a29578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=604239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43a29578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42870df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(42870df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1247): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1247): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1247): sku_id=99
D/ContactMessageStore( 1247): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1247): start background delete task...
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
,D/PMS     (  910): acquireWL(444a5cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=664239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(444a5cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c425c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  910): releaseWL(43c425c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(41ed3e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{4389fa30: PendingIntentRecord{43c21080 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=711405, Int=300000,
,D/PMS     (  910): releaseWL(41ed3e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  910): acquireWL(4406a680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=724239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4406a680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(429bd900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(429bd900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(429320a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(429320a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42953b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=784239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42953b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c0a490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  910): sending alarm PendingIntent{421be348: PendingIntentRecord{42819468 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786805, Int=0
,D/PMS     (  910): releaseWL(43c0a490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,D/PMS     (  910): acquireWL(43ae3958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  910): releaseWL(43ae3958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,D/PMS     (  910): runPSCheck
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(429ace50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(429ace50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1120): closing low battery warning: level=100
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43cf8388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=844239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43cf8388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43199800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(43199800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(443feb70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=904239, Int=0
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(443feb70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(433a9858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(433a9858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42a1f9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42a1f9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(439d7f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=964239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(439d7f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42a1d9a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/PMS     (  910): releaseWL(42a1d9a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4320d668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10028}
,V/AlarmManager(  910): sending alarm PendingIntent{44464c98: PendingIntentRecord{4282d3f8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1008631, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{426685f8: PendingIntentRecord{424e23f0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452270396077, Int=900000
D/PMS     (  910): acquireWL(429cf9f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1368 10028 null
,V/AlarmManager(  910): sending alarm PendingIntent{42917b20: PendingIntentRecord{43ce5aa8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452270467473, Int=0
,D/PMS     (  910): releaseWL(429cf9f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  910): acquireWL(42f12cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/PMS     (  910): releaseWL(42f12cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4649): call getInstance()
,D/SmartSyncUtils( 4649): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4649): MY_DEBUG = false
D/PMS     (  910): acquireWL(444c2660): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4649 1000 null
D/PMS     (  910): releaseWL(4320d668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4649): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4649): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4649): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4649): SettingOnTime = 1452319200000, randomSettingOnTime = 1452317140000
,D/SmartSyncScreenOnOffTimeReceiver( 4649): SettingOffTime = 1452297600000, randomSettingOffTime = 1452301355000
,D/SmartSyncScreenOnOffTimeReceiver( 4649): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4649): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4649): bNightModeTurnOffOnce = false
D/PMS     (  910): releaseWL(444c2660): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(4445baf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4445baf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43cd9d70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
,D/GCM     ( 1368): Message class mow
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): acquireWL(43cd9768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/PMS     (  910): releaseWL(43cd9d70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  910): releaseWL(43cd9768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=11 [335][40][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(43c3d968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1024239, Int=0
,D/PMS     (  910): releaseWL(43c3d968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c3d450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(43c3d450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(438518b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(438518b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(428a2f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1084238, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(428a2f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42974a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42974a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42405c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42405c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(427552e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1144238, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(427552e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43883058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(43883058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4206bd50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(4206bd50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42938c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1204238, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42938c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42785038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42785038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(4240eaa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(4240eaa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42921f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1264239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42921f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c7eed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43c7eed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42a50930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1324238, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42a50930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(428bc2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(428bc2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1),
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4399c4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4399c4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42a42e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1384239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42a42e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(428f7910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(428f7910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(429c6810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(429c6810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(428bf200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1444239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(428bf200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c24760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43c24760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42410538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42410538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(429217c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1504238, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(429217c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(44372228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1120): closing low battery warning: level=100
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(44372228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42730690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42730690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(429c7318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1564238, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(429c7318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42933848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42933848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42823338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42823338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/HtcPowerSaver(  910): updateBatteryInfo
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1616): [EventService] reorderNotification, total:1
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1646): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
W/ContextImpl( 4649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4171): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4171): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 4171): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4171): Cust_ConnectToPC   : spcsc>false
,D/        ( 4171): Cust_ConnectToPC   : IPT>true
D/        ( 4171): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4171): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4171): Index of the first 1 = -1
W/ContextImpl( 4171): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4171): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4171): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4171): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4171): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4171): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 4171): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(427a7d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(427a7d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(428a8270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1624239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(428a8270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42941c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42941c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(428d5120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(428d5120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4446ed48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1684239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4446ed48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4338ef38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
D/PMS     (  910): releaseWL(4338ef38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1),
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43bd6518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{421be348: PendingIntentRecord{42819468 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1506832, Int=0
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  910): sending alarm PendingIntent{4216a398: PendingIntentRecord{4287abf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1708240, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{4320fa68: PendingIntentRecord{42a17f80 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452270669849, Int=1800000
,D/PMS     (  910): acquireWL(4317c1e8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,D/PMS     (  910): acquireWL(4442d758): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1231 10028 null
D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(429f6308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(43bd6518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  910): acquireWL(4274c6f0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1231 10028 null
,D/PMS     (  910): releaseWL(4442d758): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1231): Aggregate from 1452269563017 (log), 1452268869800 (data)
,D/PMS     (  910): releaseWL(4274c6f0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=2 [45][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(429f51e0): PARTIAL_WAKE_LOCK  *sync*/com.htc.showme/com.htc.showme/***** 0x1 910 1000 WorkSource{10082}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  910): Start proc com.htc.showme for service com.htc.showme/.sync.SyncService: pid=4774 uid=10082 gids={50082, 3003, 5012, 1028, 1015}
D/PMS     (  910): acquireWL(43abfdf8): PARTIAL_WAKE_LOCK  *sync*/gmail-ls/com.google/***** 0x1 910 1000 WorkSource{10107}
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  910): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=4786 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4317c1e8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  910): releaseWL(429f6308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4338e2f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(4338e2f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4385a6b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4385a6b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/[AppShowMeDebug]SyncAdapter( 4774): onPerformSync() 
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.showme (4774/10082)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/[AppShowMeDebug]CheckUpdateTask( 4774): check and download urlSKUBased = http://showme.htctouch.com/prod/LU15A_CTH=401/; urlDeviceBased = http://showme.htctouch.com/prod/LU15A_CTH/; urlSKUTestDeviceBased = http://showme-test.htc.com.tw/testpub/LU15A_CTH=401/; urlTestDeviceBased = http://showme-test.htc.com.tw/testpub/LU15A_CTH/
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,W/GAV2    ( 4786): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4445b458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4445b458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(4442e148): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 4774): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 4
D/libc    ( 4774): [NET] getaddrinfo-,err=8
D/libc    ( 4774): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    ( 4774): [NET] getaddrinfo-, 1
,D/libc    ( 4774): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =f6dc +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(4442e148): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  9,10): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(4438d738): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(4438d738): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/Gmail   ( 4786): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4786): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  357): [NET]res_nsend:resplen=246
D/libc    (  357): [NET]res_queryN: exit 3, ancount=6
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4774): [NET] getaddrinfo_proxy-, success
,I/Gmail   ( 4786): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4786): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gm (4786/10107)
,I/Gmail   ( 4786): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5334, normalSync: true
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com mail
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc    ( 4774): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 4
D/libc    ( 4774): [NET] getaddrinfo-,err=8
D/libc    ( 4774): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    ( 4774): [NET] getaddrinfo-, 1
,D/libc    ( 4774): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =e9be +++++
,D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  357): [NET]res_queryN: exit 3, ancount=6
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4774): [NET] getaddrinfo_proxy-, success
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1368): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1368): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1368): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41ef73c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 25 4 12
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com mail
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1368): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1368): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1368): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{4225b318 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 6 12 5 12
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(433e81f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(43abfdf8): PARTIAL_WAKE_LOCK  *sync*/gmail-ls/com.google/***** 0x1 WorkSource{10107}
,D/SyncManager(  910): failed sync operation  u0 (com.google), gmail-ls, PERIODIC, latestRunTime 1708302, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), gmail-ls, PERIODIC, latestRunTime 1709573, reason: Periodic
,D/Process (  910): killProcessQuiet, pid=4357
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4357:com.android.settings:remote/1000 (adj 15): empty #17
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1434/10028)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  910): Recipient 4357
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl8,0211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
E/ExternalAccountType( 1327): Unsupported attribute readOnly
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(43c1e600): PARTIAL_WAKE_LOCK  *sync*/subscribedfeeds/com.google/***** 0x1 910 1000 WorkSource{10028}
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(433e81f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(43501300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/[AppShowMeDebug]SyncAdapter( 4774): Sync task finished
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 1,7
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  910): releaseWL(43501300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(444c83e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(444c83e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43904c70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/Process (  910): killProcessQuiet, pid=4113
D/PMS     (  910): releaseWL(429f51e0): PARTIAL_WAKE_LOCK  *sync*/com.htc.showme/com.htc.showme/***** 0x1 WorkSource{10082}
,I/ActivityManager(  910): Killing 4113:com.android.vending/u0a73 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (,  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(443950d0): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 910 1000 WorkSource{10108}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/GLSUser ( 1368): GoogleAccountDataService.getToken()
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com mail
I/ActivityManager(  910): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=4834 uid=10108 gids={50108, 3003, 5012}
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  910): releaseWL(43904c70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 116,2): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  910): Recipient 4113
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,W/AbstractGoogleClient( 4834): Application name is not set. Call Builder#setApplicationName.
,W/GLSActivity( 1368): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1368): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1368): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(44694380): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(44694380): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{422c5000 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/PMS     (  910): acquireWL(43fc5030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,I/RemoteViews.Performance( 1120): com.google.android.gms 92 19 6 12
,D/SyncManager(  910): failed sync operation  u0 (com.google), subscribedfeeds, PERIODIC, latestRunTime 1708312, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), subscribedfeeds, PERIODIC, latestRunTime 1710048, reason: Periodic
,D/PMS     (  910): releaseWL(43c1e600): PARTIAL_WAKE_LOCK  *sync*/subscribedfeeds/com.google/***** 0x1 WorkSource{10028}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1434/10028)
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  ,910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1327): Unsupported attribute readOnly
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(439d81b8): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts/com.google/***** 0x1 910 1000 WorkSource{10028}
D/PMS     (  910): releaseWL(43fc5030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43935550): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43935550): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4245d548): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(4245d548): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/calendar
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com cp
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1368): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1368): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1368): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/CalendarSyncAdapter( 4834): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 4834): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 4834): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 4834): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 4834): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:836)
E/CalendarSyncAdapter( 4834): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:412)
E/CalendarSyncAdapter( 4834): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:345)
E/CalendarSyncAdapter( 4834): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:463)
E/CalendarSyncAdapter( 4834): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 4834): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 4834): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 4834): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 4834): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 4834): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 4834): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 4834): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 4834): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 4834): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 4834): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 4834): 	... 12 more
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41f344d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42924610): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/ContactsSyncAdapter( 1368): innerSync failed
D/ContactsSyncAdapter( 1368): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1368): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1368): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1368): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1368): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1368): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1368): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1368): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
D/ContactsSyncAdapter( 1368): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1368): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
D/ContactsSyncAdapter( 1368): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
D/ContactsSyncAdapter( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,D/SyncManager(  910): failed sync operation  u0 (com.google), com.android.calendar, PERIODIC, latestRunTime 1708323, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.calendar, PERIODIC, latestRunTime 1710393, reason: Periodic
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 10 3 12
,D/Process (  910): killProcessQuiet, pid=4441
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  910): releaseWL(443950d0): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 WorkSource{10108}
I/ActivityManager(  910): Killing 4441:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1434/10028)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/RemoteViews( 1120): com.google.android.gms (false,0)
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{421ec3b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
I/ActivityManager(  910): Recipient 4441
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/RemoteViews.Performance( 1120): com.google.android.gms 1 8 2 12
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(427e33d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.plus.action/com.google/***** 0x1 910 1000 WorkSource{10028}
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
E/ExternalAccountType( 1327): Unsupported attribute readOnly
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(42924610): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(428f27f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/SyncManager(  910): failed sync operation  u0 (com.google), com.android.contacts, PERIODIC, latestRunTime 1708335, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts, PERIODIC, latestRunTime 1710477, reason: Periodic
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
D/PMS     (  910): releaseWL(428f27f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43161f50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(439d81b8): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts/com.google/***** 0x1 WorkSource{10028}
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1434/10028)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): acquireWL(429c73a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.videos.sync/com.google/***** 0x1 910 1000 WorkSource{10165}
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1327): Unsupported attribute readOnly
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  910): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=4850 uid=10165 gids={50165, 3003, 5012, 1028, 1015, 3002}
D/PMS     (  910): releaseWL(43161f50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(43ecc7e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(43ecc7e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNativ,e-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(428a29b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(428a29b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(437d2238): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(427e33d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.plus.action/com.google/***** 0x1 WorkSource{10028}
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): acquireWL(4315f328): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.cloudprint.cloudprintprovider/com.google/***** 0x1 910 1000 WorkSource{10097}
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  910): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=4865 uid=10097 gids={50097, 3003, 5012, 1028}
,D/PMS     (  910): releaseWL(437d2238): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,V/com.google.android.apps.common.multidex.Tracer( 4865): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4865): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4865): Package last updated: Mar 27, 2015 8:20:30.0
,V/com.google.android.apps.common.multidex.Tracer( 4865): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4865): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4865): Package last updated: Mar 27, 2015 8:20:30.0
,V/com.google.android.apps.common.multidex.Tracer( 4865): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@41ef4710, com.google.android.apps.common.multidex.IcsClassLoaderExtender@41ef5480, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@41ef57d8]
,V/com.google.android.apps.common.multidex.Tracer( 4865): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@41ef4710.
,D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.google.android.videos (4850/10165)
V/com.google.android.apps.common.multidex.Tracer( 4865): Patching was successful.
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4383bae8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(4383bae8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  910): Start proc com.google.android.apps.cloudprint for content provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider: pid=4881 uid=10097 gids={50097, 3003, 5012, 1028}
,V/com.google.android.apps.common.multidex.Tracer( 4881): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4881): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4881): Package last updated: Mar 27, 2015 8:20:30.0
,V/com.google.android.apps.common.multidex.Tracer( 4881): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4881): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4881): Package last updated: Mar 27, 2015 8:20:30.0
V/com.google.android.apps.common.multidex.Tracer( 4881): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@41ef8b90, com.google.android.apps.common.multidex.IcsClassLoaderExtender@41ef9900, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@41ef9c58]
,V/com.google.android.apps.common.multidex.Tracer( 4881): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@41ef8b90.
,V/com.google.android.apps.common.multidex.Tracer( 4881): Patching was successful.
,D/PlayMovies( 4850): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
D/MediaRouterService(  910): Client com.google.android.videos (pid 4850): Registered
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,I/MediaRouter( 4850): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,D/PlayMovies( 4850): MediaRouteManager.maybeRestoreRoute:188 sessionRestore routeId: 
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.videos (4850/10165)
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PlayMovies( 4850): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4865): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
D/libc    ( 4865): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4865): [NET] getaddrinfo-,err=8
D/libc    ( 4865): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4865): [NET] getaddrinfo-, 1
D/libc    ( 4865): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =3c04 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{4224e240 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/PlayMovies( 4850): TransferService.onCreate:52 creating transfer service
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43520f48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 11 4 12
D/PMS     (  910): releaseWL(43520f48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.videos (4850/10165)
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  357): [NET]res_nsend:resplen=48
D/libc    (  357): [NET]res_queryN: exit 3, ancount=1
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.videos (4850/10165)
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4865): [NET] getaddrinfo_proxy-, success
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=com.google.android.videos.pinning.TransferService$Receiver, state=1, flag=1, pid=4850, uid=10165, userID:0
,D/MediaRouter( 4850): getSelectedRoute
,D/PlayMovies( 4850): MediaRouteManager.onRouteAdded:140 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
,D/PlayMovies( 4850): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4850): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.videos/files/Movies
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.videos (4850/10165)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.videos (4850/10165)
,D/PMS     (  910): acquireWL(439034d0): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.videos (4850/10165)
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=com.google.android.videos.pinning.TransferService$Receiver, state=2, flag=1, pid=4850, uid=10165, userID:0
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
D/PMS     (  910): releaseWL(439034d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(444570b0): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  910): releaseWL(444570b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/RemoteViews( 1120): com.google.android.gms (false,0)
E/PlayMovies( 4850): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:70 Cannot get user auth
E/PlayMovies( 4850): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 4850): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 4850): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 4850): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:60)
E/PlayMovies( 4850): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:183)
E/PlayMovies( 4850): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 4850): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:223)
E/PlayMovies( 4850): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,E/PlayMovies( 4850): AccountManagerWrapper.blockingAuthenticate:165 Authentication failed
E/PlayMovies( 4850): com.google.android.videos.accounts.AccountManagerWrapper$AuthTokenException: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 4850): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:71)
E/PlayMovies( 4850): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:183)
E/PlayMovies( 4850): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 4850): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:223)
E/PlayMovies( 4850): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/PlayMovies( 4850): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 4850): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 4850): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 4850): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:60)
E/PlayMovies( 4850): 	... 4 more
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{422c94a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42893c20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/SyncManager(  910): failed sync operation  u0 (com.google), com.google.android.videos.sync, PERIODIC, latestRunTime 1708356, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.videos.sync, PERIODIC, latestRunTime 1711263, reason: Periodic
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
I/RemoteViews.Performance( 1120): com.google.android.gms 1 11 3 12
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(4447b958): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
D/PMS     (  910): releaseWL(429c73a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.videos.sync/com.google/***** 0x1 WorkSource{10165}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1434/10028)
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(4447b958): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/Process (  910): killProcessQuiet, pid=3884
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  910): acquireWL(43a31f10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.magazines/com.google/***** 0x1 910 1000 WorkSource{10151}
,I/ActivityManager(  910): Killing 3884:com.google.android.music:main/u0a154 (adj 15): empty #17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
E/ExternalAccountType( 1327): Unsupported attribute readOnly
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(42862d58): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
D/PMS     (  910): releaseWL(42893c20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(43ed2488): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
,D/PMS     (  910): releaseWL(42862d58): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): acquireWL(4351a358): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(43ed2488): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): releaseWL(4351a358): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(43bce2c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,I/SyncAdapterService( 4546): Ignoring sync request for non-current account
D/PMS     (  910): releaseWL(43bce2c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(439fce08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4546/10151)
,D/PMS     (  910): releaseWL(43a31f10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.magazines/com.google/***** 0x1 WorkSource{10151}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(443fd400): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(443fd400): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1231/10028)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(427844f8): PARTIAL_WAKE_LOCK  *sync*/com.htc.cloudstorage.drive.db/com.google/***** 0x1 910 1000 WorkSource{10068}
,I/ActivityManager(  910): Start proc com.htc.cloudstorage.drive for service com.htc.cloudstorage.drive/.SyncService: pid=4919 uid=10068 gids={50068, 3003, 5012, 1028, 1015}
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4865): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/PMS     (  910): releaseWL(439fce08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41ef1bf0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  910): Recipient 3884
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  910): Client com.google.android.music (pid 3884): Died!
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 9 4 12
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/CloudStorageManager( 4919): [getInstance] googledrive version: 6
,I/RemoteViews( 1120): com.google.android.gms (false,0)
D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4865): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{42279080 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4865): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4865): [NET] getaddrinfo-,err=8
D/libc    ( 4865): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4865): [NET] getaddrinfo-, 1
,D/libc    ( 4865): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =ee1e +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  357): [NET]res_queryN: exit 3, ancount=1
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4865): [NET] getaddrinfo_proxy-, success
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 10 4 12
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42d35990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(42d35990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GA-SERVICE( 1231): Thread[Thread-111,5,main]:  Using destination https://ssl.google-analytics.com
,W/MyGoogleDrive( 4919): [4933][GoogleDriveThreadedSyncAdapter] [onPerformSync]*Sync ABORT* Account not found(never cached)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(444540b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(427844f8): PARTIAL_WAKE_LOCK  *sync*/com.htc.cloudstorage.drive.db/com.google/***** 0x1 WorkSource{10068}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,W/GA-SERVICE( 1231): Thread[Thread-111,5,main]:  Using destination https://ssl.google-analytics.com
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): acquireWL(444273f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.music.MusicContent/com.google/***** 0x1 910 1000 WorkSource{10154}
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
I/ActivityManager(  910): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=4934 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/PMS     (  910): releaseWL(444540b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/MusicStore( 4934): Database version: 95
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4865): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41ee86e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/ContextImpl( 4934): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 6 3 12
,W/ContextImpl( 4934): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4934, uid=10154, userID:0
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4865): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,I/RemoteViews( 1120): com.google.android.gms (false,0)
D/MediaRouterService(  910): Client com.google.android.music (pid 4934): Registered
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{421eb4e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/MediaRouter( 4934): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/RemoteViews.Performance( 1120): com.google.android.gms 1 7 4 12
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,I/NetworkMonitor( 4934): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{42298b38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4865): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(426c3358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4934/10154)
,D/PMS     (  910): releaseWL(426c3358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    ( 4865): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4865): [NET] getaddrinfo-,err=8
I/RemoteViews.Performance( 1120): com.google.android.gms 1 6 3 12
D/libc    ( 4865): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4865): [NET] getaddrinfo-, 1
D/libc    ( 4865): [NET] getaddrinfo_proxy+
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/libc    (  357): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =acaa +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  357): [NET]res_queryN: exit 3, ancount=1
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4865): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,D/MediaRouter( 4934): getSelectedRoute
,I/NetworkMonitor( 4934): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4934/10154)
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4934, uid=10154, userID:0
,I/ConfigStore( 4934): Config Database version: 1
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com sj
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1368): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1368): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1368): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1120): com.google.android.gms (false,0)
D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4865): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/MusicSyncAdapter( 4934): Sync failed due to an authentication issue.
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(426be6a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{423feeb8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/SyncManager(  910): failed sync operation  u0 (com.google), com.google.android.music.MusicContent, PERIODIC, latestRunTime 1708403, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.music.MusicContent, PERIODIC, latestRunTime 1712297, reason: Periodic
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 24 4 12
,D/PMS     (  910): releaseWL(444273f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.music.MusicContent/com.google/***** 0x1 WorkSource{10154}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4934): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1434/10028)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews( 1120): com.google.android.gms (false,0)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(424da710): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4934 10154 null
D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41f487a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/RemoteViews.Performance( 1120): com.google.android.gms 1 10 4 12
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(43d57b98): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 910 1000 WorkSource{10096}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ContextImpl( 4934): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/PMS     (  910): releaseWL(426be6a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  910): acquireWL(44338de8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4934): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/PMS     (  910): releaseWL(44338de8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/DelayedSyncController( 4529): Delaying sync.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4317c6a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(4317c6a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(444560b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43d57b98): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/GLSUser ( 1368): GoogleAccountDataService.getToken()
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/ArtDownloadService( 4934): Setting cache size 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/PMS     (  910): acquireWL(4305b1b0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 910 1000 WorkSource{10100}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ArtDownloadService( 4934): Setting cache size 0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4934): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
I/ActivityManager(  910): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4973 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  910): releaseWL(444560b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/com.google.android.apps.cloudprint.net.SessionProvider( 4865): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{42040360 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 11 3 12
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/MusicLeanback( 4934): Conditions not met for autocaching.
,I/MusicLeanback( 4934): Stop autocaching.
,W/ContextImpl( 4934): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/cache
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4934, uid=10154, userID:0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/PMS     (  910): releaseWL(424da710): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,D/Process (  910): killProcessQuiet, pid=4493
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4493:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  910): Recipient 4493
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4865): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/libc    ( 4865): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4865): [NET] getaddrinfo-,err=8
D/libc    ( 4865): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4865): [NET] getaddrinfo-, 1
,D/libc    ( 4865): [NET] getaddrinfo_proxy+
,D/libc    (  357): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =8582 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  357): [NET]res_queryN: exit 3, ancount=1
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4865): [NET] getaddrinfo_proxy-, success
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{42216a50 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 2 6 3 12
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(428a2740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,I/ActivityManager(  910): Killing 4599:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,D/Process (  910): killProcessQuiet, pid=4599
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  910): killProcessQuiet, pid=4149
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4315f328): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.cloudprint.cloudprintprovider/com.google/***** 0x1 WorkSource{10097}
,I/ActivityManager(  910): Killing 4149:com.google.android.apps.plus/u0a160 (adj 15): empty #18
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(42a35328): PARTIAL_WAKE_LOCK  *sync*/com.htc.task.dm/com.google/***** 0x1 910 1000 WorkSource{10067}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
I/ActivityManager(  910): Recipient 4149
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4988 uid=10067 gids={50067, 3003, 5012}
,D/PMS     (  910): releaseWL(428a2740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4973/10100)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(434db210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4973/10100)
,W/GAV2    ( 4973): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PMS     (  910): releaseWL(434db210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43a04f38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(43a04f38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  910): acquireWL(42a56098): PARTIAL_WAKE_LOCK  SyncManager 0x1 4973 10100 null
,D/WifiService(  910): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@43190118}
,I/ActivityManager(  910): Start proc com.htc.task for content provider com.htc.task/.APICProviderDecorator: pid=5016 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  910): acquireWL(4388d090): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(4388d090): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    ( 4973): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 4
D/libc    ( 4973): [NET] getaddrinfo-,err=8
D/libc    ( 4973): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 1024
D/libc    ( 4973): [NET] getaddrinfo-, 1
,D/libc    ( 4973): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =baa9 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,I/ActivityManager(  910): Recipient 4599
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Killing 4464:com.facebook.katana/u0a26 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4464
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 24
D/libc    (  357): [NET]res_nsend:resplen=49
D/libc    (  357): [NET]res_queryN: exit 3, ancount=1
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4973): [NET] getaddrinfo_proxy-, success
I/global  ( 4973): call createSocket() return a new socket.
D/libc    ( 4973): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4973): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(444a7e70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(42a35328): PARTIAL_WAKE_LOCK  *sync*/com.htc.task.dm/com.google/***** 0x1 WorkSource{10067}
D/TodoTaskshortcut( 5016): update TASK shortcut>
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,D/PMS     (  910): acquireWL(43207f80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.location.reporting/com.google/***** 0x1 910 1000 WorkSource{10028}
,D/PMS     (  910): releaseWL(444a7e70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(439cb938): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(439cb938): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  910): killProcessQuiet, pid=4689
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4689:com.htc.aurora/u0a47 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4689
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/userlocation.reporting
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  910): Recipient 4464
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com writely
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1368): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1368): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1368): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,E/HttpIssuerBase( 4973): Attempt to consume entity of HttpIssuer when no request is executing.
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{4223e5d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/HttpIssuerBase( 4973): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 4973): java.io.IOException
E/HttpIssuerBase( 4973): 	at Er.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 4973): 	at DV.b(DefaultAuthenticatedHttpIssuer.java:148)
E/HttpIssuerBase( 4973): 	at Pq.a(AccountMetadataUpdater.java:226)
E/HttpIssuerBase( 4973): 	at Pq.a(AccountMetadataUpdater.java:139)
E/HttpIssuerBase( 4973): 	at Qv.a(LegacySyncManager.java:776)
E/HttpIssuerBase( 4973): 	at Qv.a(LegacySyncManager.java:541)
E/HttpIssuerBase( 4973): 	at Qv.a(LegacySyncManager.java:95)
E/HttpIssuerBase( 4973): 	at Qx.run(LegacySyncManager.java:396)
E/HttpIssuerBase( 4973): 	at Vz.a(NetworkUtilitiesImpl.java:30)
E/HttpIssuerBase( 4973): 	at Qw.run(LegacySyncManager.java:393)
,E/SyncManager( 4973): AuthenticatorException
E/SyncManager( 4973): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 4973): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/SyncManager( 4973): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 4973): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/SyncManager( 4973): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 4973): 	at android.os.Binder.execTransact(Binder.java:412)
E/SyncManager( 4973): 	at dalvik.system.NativeStart.run(Native Method)
,W/GAV2    ( 4973): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 13 4 12
D/WifiService(  910): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@43190118}
D/PMS     (  910): releaseWL(42a56098): PARTIAL_WAKE_LOCK  SyncManager 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43bca728): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(4305b1b0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 WorkSource{10100}
D/PMS     (  910): releaseWL(43bca728): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  910): killProcessQuiet, pid=4649
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4649:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/GCoreUlr( 1434): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService }, extras=null
,D/PMS     (  910): acquireWL(43883058): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1434 10028 null
I/AdsMeasurementBroadcastReceiver( 1231): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1231): Unauthorized to start the main service
E/GCoreUlr( 1434): 
E/GCoreUlr( 1434): arx: BadAuthentication
E/GCoreUlr( 1434): 	at arj.a(SourceFile:411)
E/GCoreUlr( 1434): 	at byt.b(SourceFile:91)
E/GCoreUlr( 1434): 	at bxr.b(SourceFile:334)
E/GCoreUlr( 1434): 	at byd.b(SourceFile:355)
E/GCoreUlr( 1434): 	at byd.a(SourceFile:325)
E/GCoreUlr( 1434): 	at byd.a(SourceFile:304)
E/GCoreUlr( 1434): 	at lwj.a(SourceFile:128)
E/GCoreUlr( 1434): 	at lye.b(SourceFile:190)
E/GCoreUlr( 1434): 	at lye.a(SourceFile:137)
E/GCoreUlr( 1434): 	at lyi.onPerformSync(SourceFile:156)
E/GCoreUlr( 1434): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42a24d28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/SyncManager(  910): failed sync operation  u0 (com.google), com.google.android.location.reporting, PERIODIC, latestRunTime 1708458, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.location.reporting, PERIODIC, latestRunTime 1713408, reason: Periodic
D/PMS     (  910): releaseWL(43207f80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.location.reporting/com.google/***** 0x1 WorkSource{10028}
D/PMS     (  910): releaseWL(42a24d28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  910): acquireWL(42286028): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1434/10028)
D/PMS     (  910): releaseWL(42286028): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/GCoreUlr( 1434): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1434): Unknown pending intent to remove.
,I/GCoreUlr( 1434): Unbound from all location providers
D/PMS     (  910): acquireWL(42839848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
D/PMS     (  910): releaseWL(42839848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  910): releaseWL(43883058): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4649
D/WifiService(  910): Client connection lost with reason: 4
,D/PMS     (  910): acquireWL(438accb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(438accb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,I/GAV2    ( 4786): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  910): acquireWL(421e4160): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4934 10154 null
,W/ContextImpl( 4934): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4934): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4934, uid=10154, userID:0
,I/MusicLeanback( 4934): Conditions not met for autocaching.
,I/MusicLeanback( 4934): Stop autocaching.
D/PMS     (  910): releaseWL(421e4160): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/GAV2    ( 4973): Thread[GAThread,5,main]: No campaign data found.
,I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.google.android.videos
,I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
,D/PackageBroadcastService( 1231): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=19, title=Play Movies & TV, componentNameComponentInfo{com.google.android.videos/com.google.android.youtube.videos.EntryPoint} appsContainer=<ALLAPPS>)
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
,I/[PluginManager]RegisterService( 1412): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.videos
,I/[PluginManager]RegisterService( 1412): handle notify Blinkfeed plugin client changed
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PeopleContactsSync( 1231): CP2 sync disabled
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  910): Resuming delayed broadcast
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1231, uid=10028, userID:0
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/ActivityManager(  910): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5056 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
D/PMS     (  910): acquireWL(427842f0): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  910): releaseWL(427842f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5056, uid=10073, userID:0
,D/Finsky  ( 5056): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (5056/10073)
,D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (5056/10073)
,D/Finsky  ( 5056): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5056): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5056): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5056, uid=10073, userID:0
,D/Finsky  ( 5056): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5056): [1] 2.run: Finished loading 1 libraries.
,D/Process (  910): killProcessQuiet, pid=4171
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4171:com.android.settings/1000 (adj 15): empty #17
,I/IcingCorporaProvider( 2877): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,I/ActivityManager(  910): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5090 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Finsky  ( 5056): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5056): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  910): Recipient 4171
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
,I/IcingCorporaProvider( 2877): UpdateCorporaTask done [took 249 ms] updated apps [took 249 ms] 
I/ActivityManager(  910): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5109 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  910): acquireWL(4385ab78): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 5090 10160 null
,D/PMS     (  910): acquireWL(4284e548): PARTIAL_WAKE_LOCK  AsyncService 0x1 5090 10160 null
,D/PMS     (  910): releaseWL(4284e548): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): acquireWL(43389160): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 5090 10160 null
,D/PMS     (  910): releaseWL(4385ab78): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [17][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (5090/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (5090/10160)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/HtcFingerPrintQuickLaunchProvider( 5109): -onCreate()
,V/Settings:HtcSettingsApplication( 5109): [5109/5109] onCreate()
,D/Process (  910): killProcessQuiet, pid=4786
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  910): Killing 4786:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PMS     (  910): releaseWL(43389160): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  910): killProcessQuiet, pid=4774
I/ActivityManager(  910): Killing 4774:com.htc.showme/u0a82 (adj 15): empty #17
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4786
,I/ActivityManager(  910): Recipient 4774
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41f71f10 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,D/PMS     (  910): acquireWL(42867ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10073}
,V/AlarmManager(  910): sending alarm PendingIntent{4440add0: PendingIntentRecord{422bb518 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452271178603, Int=0
,D/Settings:HtcWirelessFeatureFlags( 5109): id/is att sku: 99/false
,W/SystemReader( 5109): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 5109): Cannot find support_harman, use default value instead
,W/SystemReader( 5109): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 5109): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5109): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5109): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5109): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]support         :false
,W/FingerprintManager( 5109): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 5109): isSupportVoWifi: null
I/ActivityManager(  910): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5109): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5109): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5109): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5109): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5109): [supportHomeButton]support         :false
,W/PackageManager(  910): Unable to load service info ResolveInfo{434db5b8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
,W/FingerprintManager( 5109): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 5109): isSupportVoWifi: null
I/ActivityManager(  910): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5109): Failed to find provider info for com.htc.vowifi
,W/asset   ( 1272): Copying FileAsset 0x62bf0f88 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41f71f10 -
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  910): start
,D/PMS     (  910): releaseWL(42867ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/PhoneApp( 1247): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1247): -- N1 =0
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,D/PhoneApp( 1247): -- N2 =0
,D/PhoneApp( 1247): -- N3 =0
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 5056): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5056): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 5056): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5056): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5056): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/PMS     (  910): acquireWL(4317bcc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4216a398: PendingIntentRecord{4287abf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1738616, Int=0
,D/PMS     (  910): acquireWL(43908300): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,D/PMS     (  910): releaseWL(4317bcc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4447ca28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(43908300): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(4447ca28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  910): acquireWL(4291ee30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10073}
,V/AlarmManager(  910): sending alarm PendingIntent{42977db8: PendingIntentRecord{437cc730 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452271194499, Int=0
,D/PMS     (  910): releaseWL(4291ee30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 5056): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  910): acquireWL(434e12c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1744239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(434e12c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(429c5278): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
,D/PMS     (  910): releaseWL(429c5278): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(43cf54c8): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
,D/PMS     (  910): releaseWL(43cf54c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(42870e00): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
,D/PMS     (  910): releaseWL(42870e00): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(446a5180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(446a5180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1120): closing low battery warning: level=98
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44394db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44394db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43bda5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4216a398: PendingIntentRecord{4287abf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1772824, Int=0
,D/PMS     (  910): acquireWL(43bd0550): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,D/PMS     (  910): releaseWL(43bda5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(43bc8740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [12][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
,D/PMS     (  910): acquireWL(439356f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 910 1000 WorkSource{10100}
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(43bd0550): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(43bc8740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(438fcda0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(438fcda0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(43398e48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(439356f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 WorkSource{10100}
,D/PMS     (  910): releaseWL(43398e48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(428c8ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4216a398: PendingIntentRecord{4287abf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1802878, Int=0
,D/PMS     (  910): acquireWL(428312a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
D/PMS     (  910): releaseWL(428c8ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42410fa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(428312a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(42410fa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  910): acquireWL(41f03c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1804239, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(41f03c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43202d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PowerUI ( 1120): closing low battery warning: level=98
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(43202d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(42182068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): releaseWL(42182068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=99
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:99 unsupport:false plugged:true
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1231/10028)
,I/ProcessStatsService(  910): Prepared write state in 45ms
,I/ProcessStatsService(  910): Pruning old procstats: /data/system/procstats/state-2016-01-07-23-22-53.bin
,W/GA-SERVICE( 1231): Thread[Thread-111,5,main]: hit:_gmsv=1-5089038&ul=en-gb&sr=720x1184&ht=1452271167135&a=616739543&sc=start&AppUID=10151&aid=com.google.android.apps.magazines&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&cd16=Ignoring+sync+request+for+non-current+account&v=1&t=appview&an=Google+Play+Newsstand&cd11=false&tid=UA-32428711-6&_u=.nOQKSTB&_v=ma1b6&cd=Debug&qt=120552&z=117
,W/GA-SERVICE( 1231): Thread[Thread-111,5,main]: hit:_gmsv=1-5089038&ev=0&ul=en-gb&sr=720x1184&ht=1452271167136&a=424780367&AppUID=10151&aid=com.google.android.apps.magazines&ea=Sync+Skipped&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&ec=Debug&v=1&t=event&el=&an=Google+Play+Newsstand&tid=UA-32428711-6&_u=.C&_v=ma1b6&cd=Debug&qt=120551&z=118
D/libc    ( 1231): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 4
D/libc    ( 1231): [NET] getaddrinfo-,err=8
D/libc    ( 1231): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    ( 1231): [NET] getaddrinfo-, 1
,D/libc    ( 1231): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =eb50 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  357): [NET]res_nsend:resplen=102
D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1231): [NET] getaddrinfo_proxy-, success
I/global  ( 1231): call createSocket() return a new socket.
D/libc    ( 1231): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1231): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  910): acquireWL(428ec268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f049d0: PendingIntentRecord{42502058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1864238, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(428ec268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4254ed30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4254ed30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=99
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(439d4108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(439d4108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5150): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5150): ====startRecUseTime====
D/htc.customization.log.level( 5150):  is 
W/CustomizationLogLevel( 5150): Level value is invalid, use default level 2
D/CustomizationManager( 5150):  Read ACC file spent 0.134 (s)
D/CIDMapFileReader( 5150): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5150): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5150): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5150): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5150): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5150): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5150): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5150): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5150): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5150): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5150): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5150): Parsing tag category name = system
I/CustomizationCIDLoader( 5150): Parsing tag category name = application
I/CustomizationCIDLoader( 5150): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5150): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5150): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5150): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5150): Parsing tag category name = Settings
D/CustomizationManager( 5150):  Read CID file spent 0.188 (s)
D/CustomizationManager( 5150):  All configurations done spent 0.188 (s)
W/HtcNativeFlag( 5150): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5150): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5150): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5150): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=5150, uid=2000 user=0
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
W/PackageSettings(  910): Skipping PackageSetting{426958a8 com.example.hello/10356} due to missing metadata
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
D/DotMatrix( 1616): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1616): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
I/acms    ( 1921): Unregistering com.test.thalitest
E/acms    ( 1921): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1434): Ignoring removeGeofence because network location is disabled.
D/PMS     (  910): acquireWL(431c49f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
D/PMS     (  910): releaseWL(431c49f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1272): Deferring update until onResume
D/Launcher( 1272): waitUntilResume // bindAppsRemoved
W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/PackageBroadcastService( 1231): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
E/ExternalAccountType( 1327): Unsupported attribute readOnly
I/ActivityManager(  910): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=5164 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/MultiDex( 5164): install
I/MultiDex( 5164): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/MultiDex( 5164): loading existing secondary dex files
I/MultiDex( 5164): load found 1 secondary dex files
I/MultiDex( 5164): install done
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  910): Delaying start of: ServiceRecord{44448128 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 1231): CP2 sync disabled
I/Icing   ( 1231): doRemovePackageData com.test.thalitest
D/PMS     (  910): acquireWL(43cd9608): PARTIAL_WAKE_LOCK  Icing 0x1 1231 10028 null
I/ProviderInstaller( 5164): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1231, uid=10028, userID:0
D/PMS     (  910): releaseWL(43cd9608): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  910): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5182 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  910): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 5182): install
I/MultiDex( 5182): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 5182): loading existing secondary dex files
I/MultiDex( 5182): load found 1 secondary dex files
I/MultiDex( 5182): install done
I/ActivityManager(  910): Resuming delayed broadcast
I/ProviderInstaller( 5182): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1412): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1412): handle notify Blinkfeed plugin client changed
I/ActivityManager(  910): Resuming delayed broadcast
D/Process (  910): killProcessQuiet, pid=1520
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  910): Killing 1520:com.htc.bgp/u0a14 (adj 15): empty #17
I/IcingCorporaProvider( 2877): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5203 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/PackageManager(  910): Unable to load service info ResolveInfo{428d5078 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 1520
W/ContextImpl( 5203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 5203): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5203): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5203): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5203): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5203): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5203): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5203): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5203): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5203): threadid=10: thread exiting with uncaught exception (group=0x41aaee30)
E/AndroidRuntime( 5203): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5203): Process: com.android.keychain, PID: 5203
E/AndroidRuntime( 5203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5203): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5203): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5203): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5203): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5203): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5203): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5203): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  910): App crashed! Process: com.android.keychain
E/SQLiteLog( 2877): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2877): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63593c18
W/dalvikvm( 2877): threadid=14: thread exiting with uncaught exception (group=0x41aaee30)
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
E/AndroidRuntime( 2877): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2877): Process: com.google.android.googlequicksearchbox:search, PID: 2877
E/AndroidRuntime( 2877): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2877): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2877): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2877): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2877): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2877): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2877): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2877): 	at cid.d(PG:186)
E/AndroidRuntime( 2877): 	at clo.g(PG:594)
E/AndroidRuntime( 2877): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2877): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2877): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2877): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2877): 	at clr.tL(PG:827)
E/AndroidRuntime( 2877): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2877): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2877): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2877): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2877): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2877): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  910): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2877): killProcess, pid=2877
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
D/Process ( 2877): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
D/Process ( 5203): killProcess, pid=5203
D/Process ( 5203): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452271369214.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  910): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  910): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  910): 	... 4 more
I/ActivityManager(  910): Recipient 5203
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.android.keychain (pid 5203) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5220 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteLog( 5164): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 5164): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca00d18
E/DriveAsyncService( 5164): disk I/O error (code 3850)
E/DriveAsyncService( 5164): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 5164): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 5164): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 5164): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 5164): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 5164): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 5164): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 5164): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 5164): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 5164): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 5164): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 5164): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 5164): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 5164): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 5164): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/AppTag  ( 5220): getInstance(Context context)
E/SQLiteLog( 5164): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 5164): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca00d18
D/AppTag  ( 5220): getInstance(Context context)
E/DocListDatabase( 5164): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 5164): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 5164): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 5164): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 5164): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 5164): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 5164): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 5164): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 5164): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 5164): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 5164): 	at chr.a(SourceFile:75)
E/DocListDatabase( 5164): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 5164): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 5164): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 5164): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 5164): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 5164): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 5164): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 5164): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 5164): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 5164): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 5164): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 5164): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5164): threadid=1: thread exiting with uncaught exception (group=0x41aaee30)
D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  910): start
I/ActivityManager(  910): Recipient 2877
I/ActivityManager(  910): Process com.google.android.googlequicksearchbox:search (pid 2877) has died.
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  910): Client com.google.android.googlequicksearchbox (pid 2877): Died!
D/WifiService(  910): Client connection lost with reason: 4
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
E/ActivityManager(  910): App crashed! Process: com.google.android.gms.drive
D/AppTag  ( 5220): onCreate()
E/AndroidRuntime( 5164): FATAL EXCEPTION: main
E/AndroidRuntime( 5164): Process: com.google.android.gms.drive, PID: 5164
E/AndroidRuntime( 5164): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5164): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 5164): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 5164): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 5164): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5164): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5164): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5164): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5164): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5164): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5164): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5164): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5164): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5164): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5164): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 5164): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 5164): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5164): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 5164): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 5164): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 5164): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 5164): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 5164): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 5164): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 5164): 	... 10 more
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
D/Process ( 5164): killProcess, pid=5164
D/Process ( 5164): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
I/ActivityManager(  910): Recipient 5164
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.gms.drive (pid 5164) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 10972ms
D/PMS     (  910): acquireWL(4283a318): PARTIAL_WAKE_LOCK  AsyncService 0x1 5090 10160 null
W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/PMS     (  910): releaseWL(4283a318): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5238 uid=10098 gids={50098, 3003, 5012}
D/Process (  910): killProcessQuiet, pid=4834
I/ActivityManager(  910): Killing 4834:com.google.android.syncadapters.calendar/u0a108 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Recipient 4834
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 5238): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5238 dbg=false s=true
I/DeviceManagement( 5238): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5238): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5238): WorkflowService: Starting workflow service
I/DeviceManagement( 5238): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41f13208] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5238): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5238): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5238): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5238): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  910): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5252 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5238): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5238): SessionStateController: Checking invariants...
D/Documents( 5252): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 5252): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5252): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5252): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5252): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5252): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5252): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5252): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5252): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5252): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5252): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5252): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5252): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5252): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5252): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5252): threadid=1: thread exiting with uncaught exception (group=0x41aaee30)
D/Process (  910): killProcessQuiet, pid=4850
D/Documents( 5252): Loading roots for com.android.externalstorage.documents
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4850:com.google.android.videos/u0a165 (adj 15): empty #17
E/AndroidRuntime( 5252): FATAL EXCEPTION: main
E/AndroidRuntime( 5252): Process: com.android.documentsui, PID: 5252
E/AndroidRuntime( 5252): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5252): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5252): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5252): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5252): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5252): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5252): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5252): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5252): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5252): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5252): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5252): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5252): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5252): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5252): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5252): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5252): 	... 10 more
E/ActivityManager(  910): App crashed! Process: com.android.documentsui
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
D/GCM     ( 1368): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452271369498.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  910): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  910): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  910): 	... 4 more
D/Process ( 5252): killProcess, pid=5252
D/Process ( 5252): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5267 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  910): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  910): Recipient 5252
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  910): killProcessQuiet, pid=4546
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  910): Killing 4546:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
I/ActivityManager(  910): Process com.android.documentsui (pid 5252) has died.
I/ActivityManager(  910): Resuming delayed broadcast
D/GCM     ( 1368): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  910): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  910): Resuming delayed broadcast
D/ExternalStorage( 5267): After updating volumes, found 1 active roots
I/ActivityManager(  910): Delay finish: com.htc.task/.TodoTaskReceiver
E/SQLiteDatabase( 5238): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5238): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5238): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5238): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5238): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5238): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5238): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5238): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5238): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5238): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5238): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5238): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 5238): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5238): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5238): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 5238): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5238): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5238): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteDatabase( 5238): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5238): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5238): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5238): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5238): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5238): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 5238): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5238): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5238): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5238): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5238): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5238): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5238): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5238): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 5238): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41f13208]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 5238): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 5238): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 5238): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5238): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 5238): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5238): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5238): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5238): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5238): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5238): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5238): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 5238): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 5238): WorkflowService: Stopping workflow service
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Recipient 4850
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  910): Client com.google.android.videos (pid 4850): Died!
I/ActivityManager(  910): Recipient 4546
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41f71f10 +
I/Prism.WidgetManager( 1272): onLoadItems() +

```
