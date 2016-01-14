#### Test 55613145b105d0b_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
--------- beginning of /dev/log/system
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4547 uid=10077 gids={50077}
D/PMS     (  906): acquireWL(43c01968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
V/AlarmManager(  906): sending alarm PendingIntent{41c64858: PendingIntentRecord{41c217a0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452763943028, Int=60000
D/PMS     (  906): releaseWL(43c01968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4547): SMSBackupAgentService started
D/SMSBackup( 4547): Checking restore status
D/SMSBackup( 4547): Restore complete
D/SMSBackup( 4547): cancelCheckAlarm
D/SMSBackup( 4547): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  906): killProcessQuiet, pid=3906
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3906:com.google.android.music:main/u0a154 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3906): Died!
I/ActivityManager(  906): Recipient 3906
E/cutils-trace( 4562): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4562): ====startRecUseTime====
D/htc.customization.log.level( 4562):  is 
W/CustomizationLogLevel( 4562): Level value is invalid, use default level 2
D/CustomizationManager( 4562):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4562): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4562): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4562): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4562): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4562): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4562): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4562): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4562): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4562): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4562): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4562): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4562): Parsing tag category name = system
I/CustomizationCIDLoader( 4562): Parsing tag category name = application
I/CustomizationCIDLoader( 4562): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4562): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4562): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4562): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4562): Parsing tag category name = Settings
D/CustomizationManager( 4562):  Read CID file spent 0.103 (s)
D/CustomizationManager( 4562):  All configurations done spent 0.103 (s)
W/HtcNativeFlag( 4562): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4562): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4562): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4562): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4562
D/PMS     (  906): acquireHCC(434deea0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(4385e1a0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x627e2f60 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1119142760
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d5de38
I/SocialFeedProvider( 1275): +onPause
I/SocialFeedProvider( 1275): -onPause
D/PMS     (  906): acquireWL(440b66d8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4573 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1275): [trimMemory] 20
W/asset   ( 4573): Copying FileAsset 0x5c790428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4573): Binding Chromium to main looper Looper (main, tid 1) {41b25498}
I/LibraryLoader( 4573): Expected native library version number "",actual native library version number ""
I/chromium( 4573): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4573): Initializing chromium process, renderers=0
D/WIFI_ICON( 1120): WifiActivity: 1
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/PMS     (  906): acquireWL(42b1ce10): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(42e49c10): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(42b1ce10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e36498:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4573): 1102294736: getState(). Returning 12
I/Adreno-EGL( 4573): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4573): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4573): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4573): Local Branch: 
I/Adreno-EGL( 4573): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4573): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4573):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4573): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4573): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4573): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4573): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4573): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4573): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4573): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4573): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4573): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4573): CordovaWebView is running on device made by: HTC
W/AwContents( 4573): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1275
W/ResourceType( 4573): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4573): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b6c580, mServedView=org.apache.cordova.engine.SystemWebView{41b321e8 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  906): Enable input method client, pid=4573
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +426ms
W/AwContents( 4573): nativeOnDraw failed; clearing to background color.
D/PMS     (  906): releaseWL(440b66d8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4573): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4573): JniHelper::setJavaVM(0x415f7048), pthread_self() = 1663229536
D/JX-Cordova( 4573): jxcore cordova android initializing
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 11.594MB for 95956-byte allocation
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 11.672MB for 143930-byte allocation
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 11.788MB for 215890-byte allocation
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 11.963MB for 323830-byte allocation
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 12.226MB for 485740-byte allocation
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 13.226MB for 1092904-byte allocation
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 14.132MB for 1639352-byte allocation
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(434deea0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(4385e1a0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 15.460MB for 2459024-byte allocation
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:242, mTXpacketCount:227, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 17.495MB for 3688532-byte allocation
,W/jxcore-log( 4573): Initializing JXcore engine
,W/jxcore-log( 4573): JXcore engine is ready
,W/jxcore-log( 4573): Starting JXcore engine
,W/jxcore-log( 4573): Platform android
W/jxcore-log( 4573): 
,W/jxcore-log( 4573): Process ARCH arm
W/jxcore-log( 4573): 
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): releaseWL(42e49c10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4573): JXcore Cordova bridge is ready!
I/jxcore-log( 4573): 
,W/jxcore-log( 4573): JXcore engine is started
,I/chromium( 4573): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(43b993c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=175} preTxRxSum={txSum=174 rxSum=165}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20424 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20425 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{44058218: PendingIntentRecord{424732e0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=108996, Int=0
D/PMS     (  906): releaseWL(43b993c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4573): Toggling radios to true
I/jxcore-log( 4573): 
,D/BluetoothAdapter( 4573): enable(): BT is already enabled..!
,D/WifiManager( 4573): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1274
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
,D/WifiManager( 4573): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/WifiManager( 4573): reconnect: Base Package Name=com.test.thalitest, uid=10189
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): TDLS: Tear down peers
,I/wpa_supplicant( 1175): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4573): Radios toggled
I/jxcore-log( 4573): 
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4573, uid=10189
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4573): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4573): 
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1175): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1175): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1175): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb73afbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1175):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1175): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1175): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (0)+
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
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1175): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(435a8538): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): Fast associate: Old scan results
I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
D/WifiNative-wlan0(  906):    returned true
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20425 mDataStallAlarmIntent=PendingIntent{425f0208: PendingIntentRecord{424732e0 android broadcastIntent}}
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/WifiP2pService(  906): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 3840): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 3840): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiService(  906): New client listening to asynchronous messages
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
,D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3840): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3840): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/libc    (  364): [NET] entry_id:6   entry:0xb75f6058  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb75f6398  removed 
D/libc    (  364): [NET] entry_id:10   entry:0xb75f6f08  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb75f61e0  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb75f5f88  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb75fa310  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb75fa428  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb75f6550  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb75fa0e8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb75fa4f0  removed 
D/libc    (  364): [NET] entry_id:11   entry:0xb75f7088  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  906): acquireWL(426aef08): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(4247eab0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  906): acquireWL(4266f1a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/WifiNative-wlan0(  906): doBoolean: SCAN
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  906): releaseWL(4266f1a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1364/10028)
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
D/PMS     (  906): releaseWL(426aef08): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  906): releaseWL(4247eab0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4626 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(425a1478): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(425a1478): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4420/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1883/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4420/10100)
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,I/MusicStore( 4626): Database version: 95
,W/ContextImpl( 4626): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4626): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4626): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4626): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4626): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4626, uid=10154, userID:0
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 4626): Registered
,I/MediaRouter( 4626): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (4626/10154)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2476/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4646 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
D/MediaRouter( 4626): getSelectedRoute
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4626/10154)
I/NetworkMonitor( 4626): type=WIFI subType= reason=null isConnected=false
,D/ACRA    ( 4646): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  906): killProcessQuiet, pid=4348
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4626, uid=10154, userID:0
,I/ActivityManager(  906): Killing 4348:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ACRA    ( 4646): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4646): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4646): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4646): Preparing secondary program dexes.
V/DexLibLoader( 4646): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4646): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4646): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4646): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4646): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4646): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4646): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4646): Dex already copied
D/OdexVerifier( 4646): Odex verification is skipped.
,V/DexLibLoader( 4646): Creating class loader
,V/DexLibLoader( 4646): Finished creating class loader
V/DexLibLoader( 4646): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4646): Dex already copied
D/OdexVerifier( 4646): Odex verification is skipped.
,V/DexLibLoader( 4646): Creating class loader,
V/DexLibLoader( 4646): Finished creating class loader,
V/DexLibLoader( 4646): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4646): Dex already copied
D/OdexVerifier( 4646): Odex verification is skipped.
,V/DexLibLoader( 4646): Creating class loader
,V/DexLibLoader( 4646): Finished creating class loader
V/DexLibLoader( 4646): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4646): Dex already copied
,D/OdexVerifier( 4646): Odex verification is skipped.
,V/DexLibLoader( 4646): Creating class loader
V/DexLibLoader( 4646): Finished creating class loader
,V/DexLibLoader( 4646): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4646): DexLibLoader.ensureDexLoaded took 16 ms
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4348
,W/dalvikvm( 4646): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4646): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4646): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4646): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4646): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4646): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4646): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  906): setLight #0: color=#0
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421947b0
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421947b0, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c1088
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@421a48e0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/PMS     (  906): mWirelessDisplayManager is null
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-76
I/wpa_supplicant( 1175): [NULL] b8:bc:1b:5a:18:00 freq=2452 level=-87
I/wpa_supplicant( 1175): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1175): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
D/wpa_supplicant( 1175): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1175): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1175): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1175): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1175): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1175): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1175): Add randomness: count=12 entropy=6
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
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP b8:bc:1b:5a:18:00 type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] b8:bc:1b:5a:18:00 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff,:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
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
I/wpa_supplicant( 1175): selected network = 1
D/wpa_supplicant( 1175): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb73b14e8  current_ssid=0x0
D/wpa_supplicant( 1175): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): supplicant attached completed, trigger assoc.
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1175): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1175): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1175): check if in concurrent case
I/wpa_supplicant( 1175): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1175): RSN: PMKSA cache search - network_ctx=0xb73b14e8 try_opportunistic=0
D/wpa_supplicant( 1175): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1175): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1175): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 1175): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1175): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1175): nl80211: Unsubscribe mgmt frames handle 0xb73b0718 (mode change)
D/wpa_supplicant( 1175): nl80211: Subscribe to mgmt frames with non-AP handle 0xb73b0718
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb73b0718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb73b0718
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb73b0718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb73b0718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb73b0718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb73b0718
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb73b0718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb73b0718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb73b0718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb73b0718
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1175):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1175):   * freq=2412
D/wpa_supplicant( 1175):   * Auth Type 0
D/wpa_supplicant( 1175):   * WPA Versions 0x2
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1175): nl80211: Connect request send successfully
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
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
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1175): reply (887) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-48
I/wpa_supplicant( 1175): tsf=0000000111331495
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-50
I/wpa_supplicant( 1175): tsf=0000000111331512
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2452
I/wpa_supplicant( 1175): level=-76
I/wpa_supplicant( 1175): tsf=0000000111331517
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-50
I/wpa_supplicant( 1175): tsf=0000000111331507
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=4
I/wpa_supplicant( 1175): bssid=b8:bc:1b:5a:18:00
I/wpa_supplicant( 1175): freq=2452
I/wpa_supplicant( 1175): level=-87
I/wpa_supplicant( 1175): tsf=0000000111331525
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=HUAWEI-1800
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-87
I/wpa_supplicant( 1175): tsf=0000000111331529
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-88
I/wpa_supplicant( 1175): tsf=0000000111331521
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1175): ####
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 111331495, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 111331512, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2452, timestamp: 111331517, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 111331507, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: HUAWEI-1800, BSSID: b8:bc:1b:5a:18:00, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2452, timestamp: 111331525, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2462, timestamp: 111331529, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 111331521, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 440a0300 uid:1000
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (7) end of scan result ==
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): Wireless event: cmd=0x8b15 len=20
,D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1175): nl80211: Connect event
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1175): State: ASSOCIATING -> ASSOCIATED
,D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1175): Add randomness: count=13 entropy=7
I/wpa_supplicant( 1175): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412,
D/wpa_supplicant( 1175): TDLS: Remove peers on association
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized,
,D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state CONNECTING
,D/wpa_supplicant( 1175): EAPOL: enable timer tick
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1175): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1175): Get randomness: len=32 entropy=8
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  906): Associated
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
I/wpa_supplicant( 1175): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  906): This record is existed, only update it...
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb73b09f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1175):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 11
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1175): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6edeb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1175):    broadcast key
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1175): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1175): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1175): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1175): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1175): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=6
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): set send_ind_to_ndc = 0
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1175): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1175): EAPOL authentication completed successfully
I/wpa_supplicant( 1175): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 79
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
W/dalvikvm( 4646): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3840): >>>>>WISPrService start isConnected = false<<<<<
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WISPrService( 3840): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4646): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 1
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
,D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null,
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1,
,D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(43beb2b8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425e10a8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425e10a8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,E/FbInjectorInitializer( 4646): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 388ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
D/NfcService( 1259): ScreenObserver: OFF
D/NfcService( 1259): applyRouting - 0
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@44061578)
,D/NfcService( 1259): applyRouting -2
,I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
I/InputMethodManagerService(  906): Disable input method client, pid=4573
D/PMS     (  906): acquireWL(42686088): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  906): releaseWL(42686088): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(426431f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(426431f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,D/AlarmManager(  906): ACTION_SCREEN_ON
D/NfcService( 1259): applyRouting - 0
,D/MtpService( 2476): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2476): [MTP][onReceive]-
,D/NfcService( 1259): applyRouting -2
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): acquireWL(43524c88): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
,D/PMS     (  906): releaseWL(43524c88): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/fb4a(:<default>):StaticBindingVerifier( 4646): Verify
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,I/ClockThread( 1120): stop update clock
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): SET_SCREEN_ON:On
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/NetworkPolicy(  906): updateScreenOn: false
I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1804): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1804): onScreenOn: 1452763950176
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1804): onScreenOn: 1452763950176
D/PMS     (  906): acquireWL(4403f828): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
D/PMS     (  906): releaseWL(4403f828): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c1088
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c1088, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@421a48e0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(43899360): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20426 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): SET_SCREEN_ON:Off
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1175): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1175): get_ip_address source addr = 02000000
I/wpa_supplicant( 1175): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): acquireWL(436c4f00): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,D/PMS     (  906): releaseWL(436c4f00): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  906): updateScreenOn: false
,D/WifiService(  906): New client listening to asynchronous messages
,D/ContactMessageStore( 1248): start background delete task...
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/AutoSetting( 1413): service - mHandler: cancel location update
,D/AutoSetting( 1413): service -           changes count: 0
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(42e19c68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1804): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1804): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1804): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1804): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1804): onScreenOff
D/PMS     (  906): releaseWL(42e19c68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/fb4a(:<default>):BaseAnalyticsConfig( 4646): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4646): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4646): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4368
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4368:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  906): acquireWL(43788158): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
I/ActivityManager(  906): Recipient 4368
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/PMS     (  906): acquireWL(438b24b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2225 10028 null
,D/PMS     (  906): releaseWL(43788158): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/GCM     ( 1364): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/PMS     (  906): releaseWL(438b24b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1413): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1413): Util - no network available!
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1413/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1413/10053)
,D/AutoSetting( 1413): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1413): service - mHandler: cancel location update
,D/AutoSetting( 1413): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4646): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4688 uid=10078 gids={50078, 3003, 5012}
W/fb4a(:<default>):ViewerContextManagerForUserScope( 4646): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4646): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4688): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4688): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4688): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4688): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4701 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4019
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4019:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4688/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4688/10078)
,I/ActivityManager(  906): Recipient 4019
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4688/10078)
,I/dalvikvm-heap( 4646): Grow heap (frag case) to 9.953MB for 84664-byte allocation
,D/Process (  906): killProcessQuiet, pid=4276
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4715 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 4276:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,E/dalvikvm( 4646): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4646): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
I/ActivityManager(  906): Recipient 4276
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/dalvikvm( 4646): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4646): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4646): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4646): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4646): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4646): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4646): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4646): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4646): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4646): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4646): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4646): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4646): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4646): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4646): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4646): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4715): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4715): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4715): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4646): Grow heap (frag case) to 10.054MB for 39954-byte allocation
,W/ContextImpl( 4715): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4715): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/ActivityManager(  906): Activity pause timeout for ActivityRecord{4316cc30 u0 com.test.thalitest/.MainActivity t2}
,I/dalvikvm-heap( 4646): Grow heap (frag case) to 10.130MB for 79892-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4715/10151)
,V/WebViewChromiumFactoryProvider( 4715): Binding Chromium to main looper Looper (main, tid 1) {41b1e3f0}
,I/LibraryLoader( 4715): Expected native library version number "",actual native library version number ""
,I/chromium( 4715): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4715): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4715): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(43c01d80): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(4260bb28): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(43c01d80): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4715): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4715): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4715): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4715): Local Branch: 
I/Adreno-EGL( 4715): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4715): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4715):                  aa63bbd948f41d15fc72f585e
,D/wpa_supplicant( 1175): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1175): EAPOL: disable timer tick
,I/dalvikvm-heap( 4646): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,I/NSApplication( 4715): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{423eaa30 u0 ReceiverList{423ea910 4646 com.facebook.katana/10026/u0 remote:440fbe60}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{423eaa30 u0 ReceiverList{423ea910 4646 com.facebook.katana/10026/u0 remote:440fbe60}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c57390 u0 ReceiverList{43c57330 4646 com.facebook.katana/10026/u0 remote:4390a860}}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4715/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4715/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4163/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4163/10160)
,D/Process (  906): killProcessQuiet, pid=4420
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4420:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/PMS     (  906): acquireWL(4336dcd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/AutoSetting( 1413): receiver - intent: android.intent.action.USER_PRESENT
I/ActivityManager(  906): Recipient 4420
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1413): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3840): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3840): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3840): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3840): Cust_ConnectToPC   : spcsc>false
D/        ( 3840): Cust_ConnectToPC   : IPT>true
D/        ( 3840): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3840): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3840): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3840): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3840): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/PMS     (  906): releaseWL(4336dcd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/PSReceiver( 3840): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 3840): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3840): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3840):  defaultType:0
W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/GCoreFlp( 1430): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(425f5620): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
D/PMS     (  906): releaseWL(425f5620): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4759 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4646): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4646): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4646): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/SmartSyncUtils( 4759): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(44081fd8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4759 1000 null
,D/SmartSyncUtils( 4759): getMobilePolicyEnabled, result = true
D/PMS     (  906): releaseWL(44081fd8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  906): Killing 4438:com.htc.backup/1000 (adj 15): empty #17
,D/Process (  906): killProcessQuiet, pid=4438
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4438
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4759): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4759): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4759): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@421a48e0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@421a48e0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@421a48e0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@421a48e0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42284358 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42284358 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  906): releaseWL(43beb2b8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1175): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1175): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
,D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -49, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  906): WAN detection
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3840): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@424552d0
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
,D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  906): syncGetConfiguredNetworks
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
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(435a3070): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4688/10078)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=100 [1][1][0]
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,D/PMS     (  906): acquireWL(42b22370): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I/QuickSettingWifi( 1120): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  906): acquireWL(425f9e00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2225 10028 null
D/PMS     (  906): releaseWL(42b22370): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(425f9e00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(435a3070): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): releaseWL(435a8538): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/PMS     (  906): acquireWL(42330330): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(42330330): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1883/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10075)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
I/acms    ( 1883): Checking Certificates
I/acms    ( 1883): Checking Developer Certificates
I/acms    ( 1883): Checking Application Certificates
I/acms    ( 1883): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1883): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1883): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1883): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1883): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1883): Updating next query delay: 75600000
I/mlserverapp( 1883): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1883): cancelACMSProgrammedChecks
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3928/10051)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4626/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4688/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
I/NetworkMonitor( 4626): type=WIFI subType= reason=null isConnected=true
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(434d6040): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2476/10021)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(425e0438): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4815 uid=10106 gids={50106, 3003, 5012}
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(434d6040): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(423d6520): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
,D/PMS     (  906): acquireWL(440e42b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2225 10028 null
,D/PMS     (  906): releaseWL(423d6520): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/GCM     ( 1364): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  906): releaseWL(440e42b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1364): [NET] getaddrinfo-,err=8
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1364): [NET] getaddrinfo-, 1
D/libc    ( 1364): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3c97 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  906): acquireWL(43160bf8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1364 10028 null
,D/AutoSetting( 1413): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4688): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4688): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1413): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1413): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1413/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1413/10053)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4715/10151)
D/AutoSetting( 1413): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1413): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4163/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4163/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 238
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1364): [NET] getaddrinfo_proxy-, success
,I/NewsWeather( 4815): LocationClient connecting
,D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1364): [NET] getaddrinfo-,err=8
,I/NewsWeather( 4815): NewsAccounts: 2, AllSystemAccounts 1.
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  906): acquireWL(43403b08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(43403b08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/dalvikvm( 4815): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 4815): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4815): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 4815): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 4815): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ProviderInstaller( 4815): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42659e48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42659e48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4815): Last usage 0, idle 1452763953s, sync interval 2592000s
I/NewsWeather( 4815): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4815): onConnected null
,D/PMS     (  906): acquireWL(4371ac18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/GCM     ( 1364): Connected
D/PMS     (  906): acquireWL(423eb400): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/PMS     (  906): acquireWL(42693c30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  906): releaseWL(4371ac18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
W/GCoreFlp( 1430): No location to return for getLastLocation()
I/NewsWeather( 4815): LocationClient onConnected: location null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  906): releaseWL(43160bf8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,D/PMS     (  906): releaseWL(42693c30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4815): Skip sync for lookup editions
,I/NewsWeather( 4815): syncNewsAppData traffic type BACKGROUND_POLL
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  906): releaseWL(423eb400): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(42386da0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,I/NewsWeather( 4815): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1364): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
D/PMS     (  906): releaseWL(42386da0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(42dd95f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
D/PMS     (  906): releaseWL(42dd95f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/fb4a(:<default>):UserScope( 4646): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4646): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/NewsWeather( 4815): Unrecoverable authentication exception
E/NewsWeather( 4815): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4815): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [8][0][0]
D/libc    ( 4815): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    ( 4815): [NET] getaddrinfo-,err=8
D/libc    ( 4815): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4815): [NET] getaddrinfo-, 1
D/libc    ( 4815): [NET] getaddrinfo_proxy+
D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41b6df58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =723d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
I/RemoteViews.Performance( 1120): com.google.android.gms 3 9 2 12
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=70
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4815): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4815): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4815): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4646): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4646/10026)
,E/NewsWeather( 4815): Failed to syncNewsAppData
,E/NewsWeather( 4815): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): acquireWL(4319f078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  906): releaseWL(4319f078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43648458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 70747, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(425e0438): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  906): killProcessQuiet, pid=4461
I/ActivityManager(  906): Killing 4461:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  906): releaseWL(43648458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42a891c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42a891c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  906): Recipient 4461
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=25 [8][2][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(4405c990): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4626 10154 null
,W/ContextImpl( 4626): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4626): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  906): releaseWL(4260bb28): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4626, uid=10154, userID:0
,I/MusicLeanback( 4626): Conditions not met for autocaching.
,I/MusicLeanback( 4626): Stop autocaching.,
D/PMS     (  906): releaseWL(4405c990): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/AutoSetting( 1506): service - handleMessage() stop self
,D/AutoSetting( 1506): service - onDestroy() END
,D/AutoSetting( 1506): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4481
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4481:com.htc.calendar/u0a13 (adj 15): empty #17
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =40c9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4481
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ActivityManager(  906): Sleep timeout!  Sleeping now.
,D/PMS     (  906): releaseWL(43899360): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/GAV2    ( 4715): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4573): Test app app.js loaded
I/jxcore-log( 4573): 
,I/Choreographer( 4573): Skipped 520 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4573): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4573): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b321e8 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4573): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/GAV4    ( 4815): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1413): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1413): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1413): service - requestNLP() NetworkLocationProvider not enabled
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4314cd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): releaseWL(4314cd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42aeafe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=135380, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42399478: PendingIntentRecord{41e6b2a0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452763963324, Int=563223000
,D/PMS     (  906): acquireWL(435b1040): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(44086dd8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
,D/PMS     (  906): acquireWL(425d1588): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(435b1040): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42aeafe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): releaseWL(425d1588): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(44066320): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2225 10028 null
,D/PMS     (  906): releaseWL(44086dd8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,I/CheckinService( 2225): Preparing to send checkin request
,I/EventLogService( 2225): Accumulating logs since 1452763931124
,I/GoogleHttpClient( 2225): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2225): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2225/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2225/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=23 [17][4][0]
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2225): awaiting user notification for token
,I/RemoteViews( 1120): com.google.android.gms (false,0)
D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41bb21b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 3 9 2 12
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4524/10028)
W/Settings( 4524): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4524): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4524): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4524): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4524): Local Branch: 
I/Adreno-EGL( 4524): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4524): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4524):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4524): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4524): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4524): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4524): Local Branch: 
I/Adreno-EGL( 4524): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4524): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4524):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4524): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4524): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4524): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4524): Local Branch: 
I/Adreno-EGL( 4524): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4524): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4524):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 2225): Sending checkin request (8970 bytes)
,D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2225): [NET] getaddrinfo-,err=8
D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2225): [NET] getaddrinfo-, 1
,D/libc    ( 2225): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ad66 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 222
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2225): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2225): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(4359c6c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(4359c6c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2225/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2225/10028)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=11 [17][2][0]
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2225): awaiting user notification for token
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41e2f4e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 2 10 3 12
,I/CheckinTask( 2225): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2225): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/PMS     (  906): releaseWL(44066320): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 2225): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bf7d38 that was originally bound here
E/ActivityThread( 2225): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bf7d38 that was originally bound here
E/ActivityThread( 2225): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2225): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2225): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2225): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2225): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2225): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2225): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2225): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2225): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2225): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2225): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2225): 	at bks.a(SourceFile:298)
E/ActivityThread( 2225): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2225): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2225): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2225): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1364): GCM config loaded
,D/PMS     (  906): acquireWL(43229ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=141628, Int=0
,D/PMS     (  906): releaseWL(43229ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4413ef20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{425405d8: PendingIntentRecord{424b13e8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141915, Int=0
,D/PMS     (  906): releaseWL(4413ef20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  906): acquireWL(4361c448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(4361c448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(4264d1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ac238: PendingIntentRecord{424ff000 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141954, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/PMS     (  906): acquireWL(43159130): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4264d1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =da4e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): acquireWL(426bc918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(426bc918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1413): service - has update message, not stop
,D/AutoSetting( 1413): service - mHandler: update timezone
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1506): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1567): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1506): service - mHandler: update timezone
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1506): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1506): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1120): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41b75638 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.htclocationservice 2 7 2 11
,D/PMS     (  906): acquireWL(43c5f598): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/PMS     (  906): releaseWL(43c5f598): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(431703d8): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/PMS     (  906): releaseWL(431703d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(440bfc88): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/PMS     (  906): releaseWL(440bfc88): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4298a318): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/PMS     (  906): releaseWL(4298a318): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): releaseWL(43159130): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{432b6420 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(438564f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=165404, Int=0
,D/PMS     (  906): acquireWL(434e5978): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(438564f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(426b9b38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=7 [38][3][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(43883db0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0],
D/PMS     (  906): releaseWL(434e5978): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(426b9b38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(440597c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(440597c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4815): Last usage 0, idle 1452764003s, sync interval 2592000s
I/NewsWeather( 4815): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4815): Skip sync for lookup editions
,I/NewsWeather( 4815): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4815): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4815): Unrecoverable authentication exception
E/NewsWeather( 4815): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4815): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41b3ea30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 2 8 4 12
,D/PMS     (  906): acquireWL(43abf9f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,E/NewsWeather( 4815): Failed to syncNewsAppData
,E/NewsWeather( 4815): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): releaseWL(43abf9f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(438e1fb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 115127, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(43883db0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(438e1fb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(435a5c90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(435a5c90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1413): service - handleMessage() stop self
,D/AutoSetting( 1413): service - handleMessage() quit looper
,D/AutoSetting( 1413): service - onDestroy() END
,D/AutoSetting( 1506): service - handleMessage() stop self
,D/Process (  906): killProcessQuiet, pid=3928
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3928:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3928
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AutoSetting( 1506): service - onDestroy() END
D/AutoSetting( 1506): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4407
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4407:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4407
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42db9e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{428f48a0: PendingIntentRecord{42bc27c0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=176438, Int=0
,D/PMS     (  906): releaseWL(42db9e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(42aeab10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(42aeab10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42603010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=195469, Int=0
,D/PMS     (  906): acquireWL(426022f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(42603010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(425f9fc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(426022f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(425f9fc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(4234faa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=201628, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4234faa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4202aa68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4202aa68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41db5620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(41c3daf0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=231478, Int=0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(41db5620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42515ed8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=8 [23][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(41f02b58): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,D/PMS     (  906): releaseWL(41c3daf0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42515ed8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(425c5e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,I/NewsWeather( 4815): Last usage 0, idle 1452764070s, sync interval 2592000s
,I/NewsWeather( 4815): setPeriodicSync in seconds 2592000
D/PMS     (  906): releaseWL(425c5e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4815): Skip sync for lookup editions
,I/NewsWeather( 4815): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4815): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/NewsWeather( 4815): Unrecoverable authentication exception
E/NewsWeather( 4815): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4815): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41c507b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 11 3 12
,D/PMS     (  906): acquireWL(42dbcb58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(42dbcb58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
E/NewsWeather( 4815): Failed to syncNewsAppData
E/NewsWeather( 4815): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(424dae18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 166025, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(41f02b58): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(424dae18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43782080): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
,D/PMS     (  906): releaseWL(43782080): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(425a4ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425a4ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(4248a658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=261540, Int=0
,D/PMS     (  906): acquireWL(4239d9b8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(4248a658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429930f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4239d9b8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(429930f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42383f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=261627, Int=0
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42383f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42601b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42601b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4573): TAP version 13
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # multiplex can send data
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,D/PMS     (  906): acquireWL(42112340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=321627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42112340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4573): ok 1 String should be length:200
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # basic
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 2 sane
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # another
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 3 sane
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 4 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 5 null
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 6 (unnamed assert)
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 7 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 8 should not throw
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 9 (unnamed assert)
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 10 (unnamed assert)
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 11 should not throw
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 12 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 13 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 14 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # failed to get mobile documents path
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 15 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 16 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 17 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 18 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #init should register the networkChanged event
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 19 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #startBroadcasting should throw on null device name
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 20 should throw
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 21 should throw
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 22 should throw
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 23 should throw
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #startBroadcasting should throw on negative port
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 24 should throw
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #startBroadcasting should throw on too large port
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 25 should throw
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 26 should be equal
I/jxcore-log( 4573): 
I/jxcore-log( 4573): ok 27 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 28 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 29 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 30 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 31 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 32 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 33 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 34 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 35 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 36 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 37 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 38 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 39 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 40 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 41 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 42 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 43 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): ok 44 should be equal
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # setup
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4573): 
,I/jxcore-log( 4573): # teardown
I/jxcore-log( 4573): 
,W/dalvikvm( 4573): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4573): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4573): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4573): start: Peer ID: 80:01:84:8A:B3:68, peer name: 1452764184311.4573
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4573): bind: Binding a new listener
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4573): initialize: My bluetooth address is 80:01:84:8A:B3:68
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4573): verifyIdentityString: Identity string created: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"1452764184311.4573"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4573): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 4573): getBluetoothService(): entry
,W/BluetoothAdapter( 4573): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1591): SOCK FLAG = 0 ***********************
I/bt-btif ( 1591): BTA_JvCreateRecordByUser
,D/bt-btm  ( 1591): BTM_AllocateSCN
D/bt-sdp  ( 1591): SDP_CreateRecord ok, num_records:17
I/bt-btif ( 1591): BTA_JvRfcommStartServer
I/bt-btm  ( 1591): BTM_SEC_REG[19]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
,I/bt-btm  ( 1591):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4573): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4573): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4573): start: OK
,I/io.jxcore.node.ConnectionHelper( 4573): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4573): start: Peer ID: 80:01:84:8A:B3:68, peer name: 1452764184311.4573
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4573): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 4573): bind: Binding a new listener
,W/dalvikvm( 4573): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4573): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4573): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
W/dalvikvm( 4573): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
W/dalvikvm( 4573): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4573): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 4573): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
W/dalvikvm( 4573): VFY: unable to resolve new-instance 427 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
W/dalvikvm( 4573): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 4573): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
E/dalvikvm( 4573): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
W/dalvikvm( 4573): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
,W/dalvikvm( 4573): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4573): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4573): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4573): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4573): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4573): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4573): VFY: unable to resolve virtual method 1808: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
W/dalvikvm( 4573): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4573): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4573): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4573): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4573): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4573): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4573): VFY: unable to resolve virtual method 1809: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
W/dalvikvm( 4573): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4573): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4573): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4573): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/dalvikvm( 4573): threadid=1: thread exiting with uncaught exception (group=0x416efe30)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at android.os.Looper.loop(Looper.java:157)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4573): 	at dalvik.system.NativeStart.main(Native Method)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43205ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(42dcfca8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=362953, Int=0
,D/PMS     (  906): releaseWL(43205ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43fbb218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=16 [153][26][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(4389a4a0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,D/PMS     (  906): releaseWL(42dcfca8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43fbb218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4360a9e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4360a9e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4815): Last usage 0, idle 1452764201s, sync interval 2592000s
,I/NewsWeather( 4815): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4815): Skip sync for lookup editions
,I/NewsWeather( 4815): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4815): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/NewsWeather( 4815): Unrecoverable authentication exception
E/NewsWeather( 4815): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4815): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41dd9c20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 17 7 12
,D/PMS     (  906): acquireWL(42633280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,E/NewsWeather( 4815): Failed to syncNewsAppData
,E/NewsWeather( 4815): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): releaseWL(42633280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42683830): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 232045, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(4389a4a0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(42683830): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(424e1230): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(424e1230): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,W/GLSActivity( 1364): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1364): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1364): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1364): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1364): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41b57890 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 2 9 3 12
,E/PlayEventLogger( 4126): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4126): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4126): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4126): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4126): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4126): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4126): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4126): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 4126): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4126): [NET] getaddrinfo-,err=8
D/libc    ( 4126): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4126): [NET] getaddrinfo-, 1
,D/libc    ( 4126): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1737 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4126): [NET] getaddrinfo_proxy-, success
I/global  ( 4126): call createSocket() return a new socket.
D/libc    ( 4126): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4126): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4126): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4126): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(4323cfc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4323cfc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(43df0928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=381628, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43df0928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4388caa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/PMS     (  906): acquireWL(440d4b08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=393034, Int=0
,D/PMS     (  906): releaseWL(4388caa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(437c8c50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(440d4b08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(437c8c50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42662b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42662b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42aa16e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=441627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42aa16e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(441054f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(441054f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(43b2bc78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=501627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b2bc78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(433031e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(42b4be60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=525631, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43839fa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(433031e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(42b4be60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43839fa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43ade250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43ade250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43734910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=561627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43734910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(434dcb38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(434dcb38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43198db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43198db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(437df1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=621627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437df1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1248): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1248): sku_id=99
D/ContactMessageStore( 1248): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1248): start background delete task...
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/PMS     (  906): acquireWL(4267d290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(4321a428): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=625298, Int=0
D/PMS     (  906): releaseWL(4267d290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42ddecd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=22 [44][10][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(423b6248): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,D/PMS     (  906): releaseWL(4321a428): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42ddecd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(440a2c00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(440a2c00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4815): Last usage 0, idle 1452764463s, sync interval 2592000s
,I/NewsWeather( 4815): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4815): Skip sync for lookup editions
,I/NewsWeather( 4815): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4815): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/NewsWeather( 4815): Unrecoverable authentication exception
E/NewsWeather( 4815): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4815): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41b2a1c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4815): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4815): [NET] getaddrinfo-,err=8
D/libc    ( 4815): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4815): [NET] getaddrinfo-, 1
,D/libc    ( 4815): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =11ed +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4815): [NET] getaddrinfo_proxy-, success
,I/RemoteViews.Performance( 1120): com.google.android.gms 2 15 6 12
,D/libc    ( 4815): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4815): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(425c2950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,E/NewsWeather( 4815): Failed to syncNewsAppData
,E/NewsWeather( 4815): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): releaseWL(425c2950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 363483, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43636bf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(423b6248): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
D/PMS     (  906): releaseWL(43636bf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4389ff10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4389ff10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/PMS     (  906): acquireWL(43c84be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(44084340): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=655366, Int=0
,D/PMS     (  906): releaseWL(43c84be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(431a29d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(44084340): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(431a29d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(432f6e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(432f6e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4363fba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=681627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4363fba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=4495
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4495:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4495
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4265b710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4265b710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43e049c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=741627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43e049c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440ba340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440ba340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4347b230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=801627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4347b230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43684428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43684428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42dcb4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=861627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42dcb4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43360768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43360768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42de2f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=921627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42de2f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(434d8860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(434d8860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43c58d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=981627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43c58d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(434a1c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(434a1c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43157bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41dd7888: PendingIntentRecord{4245fa88 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=788194, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4915 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{4259d020: PendingIntentRecord{4254f2c0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452764059291, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{4262ddd0: PendingIntentRecord{4264cb10 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452764779496, Int=900000
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,V/AlarmManager(  906): sending alarm PendingIntent{43b2a190: PendingIntentRecord{44075500 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452764851288, Int=0
,W/ContextImpl( 4759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4759): call getInstance()
,D/SmartSyncUtils( 4759): isEpsOn(), nState = 0
D/PMS     (  906): releaseWL(43157bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42dab940): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4759 1000 null
D/PowerUsageList:PowerUsageHelper( 4759): MY_DEBUG = false
D/SmartSyncScreenOnOffTimeReceiver( 4759): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4759): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 7, bNormalRange = true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4915/10047)
,D/SmartSyncScreenOnOffTimeReceiver( 4759): [updateNmRange] new USERNIGHT_TIMESTART = 1, new USERNIGHT_TIMEEND = 7
D/SmartSyncScreenOnOffTimeReceiver( 4759): AlarmOnTime = -1
,I/FeedHostManager( 1275): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
,I/FeedHostManager( 1275): NightMode begin at 0, end at 7
W/ContextImpl( 4759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
,D/PMS     (  906): acquireWL(43593328): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1275 10075 null
D/SmartSyncScreenOnOffTimeReceiver( 4759): SettingOnTime = 1452837600000, randomSettingOnTime = 1452836847000
D/SmartSyncScreenOnOffTimeReceiver( 4759): SettingOffTime = 1452816000000, randomSettingOffTime = 1452818671000
D/SmartSyncScreenOnOffTimeReceiver( 4759): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4759): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4759): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(42dab940): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/FeedHostManager( 1275): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1452764851430, BeginTime: 1452812400000, EndTime: 1452837600000
D/PMS     (  906): releaseWL(43593328): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/ActivityManager(  906): Killing 4218:com.google.android.configupdater/u0a16 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4218
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4218
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43c50f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{42e7d508: PendingIntentRecord{424e0068 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1014756, Int=0
,D/PMS     (  906): acquireWL(440adb60): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(440adb60): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): releaseWL(43c50f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(4237bc78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(4237bc78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(422e3ac0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,D/GCM     ( 1364): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  906): releaseWL(422e3ac0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(42551cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(42551cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=11 [42][5][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(4389a590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4389a590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(440d8988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1041627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440d8988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425eac90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425eac90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(434e77a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1101628, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(434e77a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4265b3a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/PMS     (  906): acquireWL(426bc700): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1149439, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{43be9a78: PendingIntentRecord{42629608 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452764873409, Int=1800000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4385d738): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): acquireWL(4257bf40): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2225 10028 null
,D/PMS     (  906): releaseWL(4265b3a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(4363f4a8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2225 10028 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  906): releaseWL(4257bf40): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/EventLogService( 2225): Aggregate from 1452763973807 (log), 1452763073354 (data)
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=22 [9][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42df4388): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(436073b8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 906 1000 WorkSource{10160}
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(426bc700): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(4385d738): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43b10f10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43b10f10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42cbf300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42cbf300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/NewsWeather( 4815): Last usage 0, idle 1452764987s, sync interval 2592000s
,I/NewsWeather( 4815): setPeriodicSync in seconds 2592000
D/PMS     (  906): acquireWL(434f5320): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(434f5320): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): releaseWL(4363f4a8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,I/dalvikvm-heap( 4163): Grow heap (frag case) to 13.640MB for 1821008-byte allocation
I/NewsWeather( 4815): Skip sync for lookup editions
,I/NewsWeather( 4815): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4815): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,I/dalvikvm-heap( 4163): Grow heap (frag case) to 15.343MB for 1821008-byte allocation
W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43701968): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(436073b8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/PMS     (  906): releaseWL(43701968): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/dalvikvm-heap( 4163): Grow heap (frag case) to 17.078MB for 1821008-byte allocation
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/NewsWeather( 4815): Unrecoverable authentication exception
E/NewsWeather( 4815): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4815): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4815): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/libc    ( 4815): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4815): [NET] getaddrinfo-,err=8
D/libc    ( 4815): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    ( 4815): [NET] getaddrinfo-, 1
,D/libc    ( 4815): [NET] getaddrinfo_proxy+
D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41b29590 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b5d0 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4815): [NET] getaddrinfo_proxy-, success
,I/RemoteViews.Performance( 1120): com.google.android.gms 2 11 6 12
,D/libc    ( 4815): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4815): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(4293e6f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(4293e6f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4815): Failed to syncNewsAppData
,E/NewsWeather( 4815): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(435ac678): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 625807, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(42df4388): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  906): releaseWL(435ac678): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4262f190): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4262f190): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/PMS     (  906): acquireWL(44121a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44121a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(434e86e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1161628, Int=0
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(434e86e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4358c9e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4358c9e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43219a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/PMS     (  906): acquireWL(43636370): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
V/AlarmManager(  906): sending alarm PendingIntent{41cf7c38: PendingIntentRecord{424c7b50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1179537, Int=0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(43219a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(432935e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43636370): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(432935e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(44079ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44079ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(432492f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1221627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(432492f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(436f0cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  906): releaseWL(436f0cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4262e448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1281627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4262e448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42f35c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42f35c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4336ad88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4336ad88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43550e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1341627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43550e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43afb7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43afb7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43e4ca48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43e4ca48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4403c160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1401627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4403c160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fe86d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fe86d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4293e850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1461627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4293e850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(436f2c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436f2c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(434f1858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(434f1858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(436f70d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1521627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(436f70d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4402a5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4402a5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43144df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1581628, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43144df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42bf2e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42bf2e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43d1bf70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1641628, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43d1bf70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440aace0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440aace0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(436699c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436699c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4405e6d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1701627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4405e6d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43372ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43372ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42bf3370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42bf3370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4293df70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1761627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4293df70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(431a8ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431a8ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43c13f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c13f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3840): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3840): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3840): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3840): Cust_ConnectToPC   : spcsc>false
D/        ( 3840): Cust_ConnectToPC   : IPT>true
D/        ( 3840): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3840): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3840): Index of the first 1 = 3
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3840): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3840): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3840): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3840): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3840): [ACC]android_networking:tethering_guard_support=false
,W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(444cd1d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(444cd1d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(435a3070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1821627, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  906): Prepared write state in 32ms
,I/ProcessStatsService(  906): Prepared write state in 19ms
,I/ProcessStatsService(  906): Prepared write state in 9ms
,D/PMS     (  906): releaseWL(435a3070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2016-01-13-14-08-45.bin
,D/PMS     (  906): acquireWL(435a0728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435a0728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4323a970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(4323a970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42ddb1d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c43a98: PendingIntentRecord{41c43a60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1881628, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ddb1d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42dbc330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42dbc330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/Process (  906): killProcessQuiet, pid=4126
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  906): Killing 4126:com.android.vending/u0a73 (adj 15): empty for 1810s
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  906): Recipient 4126
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(426220c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41dd7888: PendingIntentRecord{4245fa88 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1732957, Int=0
,D/Process (  906): killProcessQuiet, pid=4715
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=4701
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=4688
I/ActivityManager(  906): Killing 4715:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1800s
I/ActivityManager(  906): Killing 4701:com.android.chrome/u0a96 (adj 15): empty for 1800s
,I/ActivityManager(  906): Killing 4688:com.google.android.setupwizard/u0a78 (adj 15): empty for 1800s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=4547
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 4547:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1810s
,V/AlarmManager(  906): sending alarm PendingIntent{423a5e50: PendingIntentRecord{42526068 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821464, Int=1800000
,I/ActivityManager(  906): Recipient 4701
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4238c9b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{424d6e28: PendingIntentRecord{424e0068 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1914876, Int=0
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,V/AlarmManager(  906): sending alarm PendingIntent{4262ddd0: PendingIntentRecord{4264cb10 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452765679496, Int=900000
I/ActivityManager(  906): Recipient 4688
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(4238c9b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): acquireWL(423dcfb8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
,D/PMS     (  906): acquireWL(423cdf70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(423dcfb8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,W/ContextImpl( 4759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(423cdf70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): releaseWL(426220c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/ActivityManager(  906): Recipient 4547
I/ActivityManager(  906): Recipient 4715
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1364): Message class mow
D/PMS     (  906): acquireWL(42039eb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  906): releaseWL(42039eb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(41b6cdb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(41b6cdb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=4626
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4626:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=14 [84][12][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  906): Recipient 4626
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/MediaRouterService(  906): Client com.google.android.music (pid 4626): Died!
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4962): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4962): ====startRecUseTime====
D/htc.customization.log.level( 4962):  is 
W/CustomizationLogLevel( 4962): Level value is invalid, use default level 2
D/CustomizationManager( 4962):  Read ACC file spent 0.100 (s)
D/CIDMapFileReader( 4962): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4962): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4962): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4962): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4962): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4962): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4962): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4962): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4962): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4962): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4962): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4962): Parsing tag category name = system
I/CustomizationCIDLoader( 4962): Parsing tag category name = application
I/CustomizationCIDLoader( 4962): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4962): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4962): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4962): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4962): Parsing tag category name = Settings
D/CustomizationManager( 4962):  Read CID file spent 0.152 (s)
D/CustomizationManager( 4962):  All configurations done spent 0.153 (s)
W/HtcNativeFlag( 4962): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4962): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4962): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4962): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4962, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4573
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906): Killing 4573:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
I/ActivityManager(  906):   Force finishing activity ActivityRecord{4316cc30 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  906): Copying FileAsset 0x627e4480 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  906): channel '425d8270 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '425d8270 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/bt-btif ( 1591): BTA_JvDeleteRecord
I/bt-btif ( 1591): BTA_JvRfcommStopServer
D/bt-btm  ( 1591): BTM_FreeSCN 
D/WifiService(  906): Client connection lost with reason: 4
D/bt-sdp  ( 1591): SDP_DeleteRecord ok, num_records:16
E/bt-btif ( 1591): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1591): BTM_SEC_CLR[19]: id 58
W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '425d8270 com.test.thalitest.MainActivity (s)'
I/WindowState(  906): WIN DEATH: Window{425d8270 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/WindowManager(  906): WINDOW DIED Window{425d8270 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4573 uid 10189
W/Binder  ( 1212): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1212): java.lang.NullPointerException
W/Binder  ( 1212): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1212): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1212): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1212): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1567): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1567): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1883): Unregistering com.test.thalitest
E/acms    ( 1883): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1430): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): acquireWL(437b0290): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
D/PMS     (  906): releaseWL(437b0290): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/Launcher( 1275): Deferring update until onResume
D/Launcher( 1275): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/PackageBroadcastService( 2225): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4977 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
E/ExternalAccountType( 1332): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/ActivityManager(  906): Delaying start of: ServiceRecord{437a0450 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4977): install
I/MultiDex( 4977): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4977): loading existing secondary dex files
I/MultiDex( 4977): load found 1 secondary dex files
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4992 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 4977): install done
I/PeopleContactsSync( 2225): CP2 sync disabled
I/Icing   ( 2225): doRemovePackageData com.test.thalitest
D/PMS     (  906): acquireWL(41e31ee0): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2225, uid=10028, userID:0
D/PMS     (  906): releaseWL(41e31ee0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4992): install
I/MultiDex( 4992): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4992): loading existing secondary dex files
I/MultiDex( 4992): load found 1 secondary dex files
I/MultiDex( 4992): install done
I/ProviderInstaller( 4977): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ProviderInstaller( 4992): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1413): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1413): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5013 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4977): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4977): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4977): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4977): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4977): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4977): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4977): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4977): 	at ctn.run(SourceFile:985)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5013, uid=10073, userID:0
W/dalvikvm( 4977): threadid=12: thread exiting with uncaught exception (group=0x416efe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4977): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4977): Process: com.google.android.gms.drive, PID: 4977
E/AndroidRuntime( 4977): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4977): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4977): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4977): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4977): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4977): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4977): 	at ctn.run(SourceFile:985)
D/Process ( 4977): killProcess, pid=4977
D/Process ( 4977): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
D/Finsky  ( 5013): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (5013/10073)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (5013/10073)
W/PackageManager(  906): Unable to load service info ResolveInfo{425291b8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/Finsky  ( 5013): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 5013): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5013): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 5013): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 5013): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5013): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5013): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5013): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 5013): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 5013): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 5013): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 5013): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5013): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5013): threadid=25: thread exiting with uncaught exception (group=0x416efe30)
E/ActivityManager(  906): App crashed! Process: com.android.vending
E/AndroidRuntime( 5013): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 5013): Process: com.android.vending, PID: 5013
E/AndroidRuntime( 5013): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5013): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5013): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5013): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5013): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 5013): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 5013): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 5013): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5013): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5013): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5013, uid=10073, userID:0
D/Process ( 5013): killProcess, pid=5013
D/Process ( 5013): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
I/IcingCorporaProvider( 2910): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5049 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Recipient 4977
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4977) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
E/SQLiteLog( 2910): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2910): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63e25908
W/dalvikvm( 2910): threadid=15: thread exiting with uncaught exception (group=0x416efe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2910): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2910): Process: com.google.android.googlequicksearchbox:search, PID: 2910
E/AndroidRuntime( 2910): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2910): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2910): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2910): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2910): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2910): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2910): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2910): 	at cid.d(PG:186)
E/AndroidRuntime( 2910): 	at clo.g(PG:594)
E/AndroidRuntime( 2910): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2910): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2910): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2910): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2910): 	at clr.tL(PG:827)
E/AndroidRuntime( 2910): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2910): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2910): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2910): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2910): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Recipient 5013
I/ActivityManager(  906): Process com.android.vending (pid 5013) has died.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process ( 2910): killProcess, pid=2910
D/Process ( 2910): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
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
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2910
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2910) has died.
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2910): Died!
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
D/WifiService(  906): Client connection lost with reason: 4
E/SQLiteDatabase( 5049): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5049): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5049): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5049): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5049): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5049): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5049): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5049): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5049): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5049): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5049): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5049): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5049): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5049): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5049): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5049): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5049): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5049): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5049): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5049): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5049): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5049): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5049): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5049): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5049): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5049): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5049): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5049): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5049): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5049): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5049): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5049): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5049): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5049): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5049): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5049): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5049): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5049): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5049): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5049): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5049): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5049): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5049): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5049): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5049): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5049): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5049): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5049): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5049): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5049): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5049): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5049): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5049): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5049): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5049): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5049): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5049): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5049): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5049): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5049): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5049): threadid=11: thread exiting with uncaught exception (group=0x416efe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5049): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5049): Process: com.google.android.apps.docs, PID: 5049
E/AndroidRuntime( 5049): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5049): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5049): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5049): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5049): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5049): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 5049): killProcess, pid=5049
D/Process ( 5049): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5065 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 5049
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 5049) has died.
W/ContextImpl( 5065): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5078 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5065): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5065): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5065): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5065): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5065): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5065): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5065): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5065): threadid=10: thread exiting with uncaught exception (group=0x416efe30)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5065): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5065): Process: com.android.keychain, PID: 5065
E/AndroidRuntime( 5065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5065): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5065): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5065): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5065): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5065): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5065): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5065): killProcess, pid=5065
D/Process ( 5065): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452765757220.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 5065
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 5065) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10606ms
D/AppTag  ( 5078): getInstance(Context context)
D/AppTag  ( 5078): getInstance(Context context)
D/AppTag  ( 5078): onCreate()
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41bb2e10 +
I/Prism.WidgetManager( 1275): onLoadItems() +
D/PMS     (  906): acquireWL(4363bdf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4163 10160 null
D/PMS     (  906): releaseWL(4363bdf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5096 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 5096): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5096 dbg=false s=true
I/DeviceManagement( 5096): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5096): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5096): WorkflowService: Starting workflow service
I/DeviceManagement( 5096): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b4cd10] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5096): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5096): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5096): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5096): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5110 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5096): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5096): SessionStateController: Checking invariants...
D/Documents( 5110): Loading roots for com.android.providers.downloads.documents
D/Documents( 5110): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5110): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5110): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5110): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5110): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5110): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5110): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5110): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5110): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5110): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5110): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5110): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5110): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5110): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5110): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5110): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5110): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5110): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5110): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5110): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5110): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5110): threadid=1: thread exiting with uncaught exception (group=0x416efe30)
E/AndroidRuntime( 5110): FATAL EXCEPTION: main
E/AndroidRuntime( 5110): Process: com.android.documentsui, PID: 5110
E/AndroidRuntime( 5110): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5110): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5110): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5110): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5110): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5110): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5110): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5110): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5110): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5110): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5110): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5110): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5110): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5110): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5110): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5110): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5110): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5110): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5110): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5110): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5110): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5110): 	... 10 more
E/ActivityManager(  906): App crashed! Process: com.android.documentsui
D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5124 uid=10023 gids={50023, 1028, 1015, 1023}
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5110): killProcess, pid=5110
D/Process ( 5110): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452765757525.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 5110
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Process com.android.documentsui (pid 5110) has died.
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Resuming delayed broadcast
D/ExternalStorage( 5124): After updating volumes, found 1 active roots
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5140 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}

```
