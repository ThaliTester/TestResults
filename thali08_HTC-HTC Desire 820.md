#### Test 561510933390750_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
E/cutils-trace( 4447): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4447): ====startRecUseTime====
D/htc.customization.log.level( 4447):  is 
W/CustomizationLogLevel( 4447): Level value is invalid, use default level 2
D/CustomizationManager( 4447):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4447): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4447): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4447): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4447): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4447): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4447): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4447): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4447): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4447): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4447): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4447): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4447): Parsing tag category name = system
I/CustomizationCIDLoader( 4447): Parsing tag category name = application
I/CustomizationCIDLoader( 4447): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4447): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4447): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4447): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4447): Parsing tag category name = Settings
D/CustomizationManager( 4447):  Read CID file spent 0.097 (s)
D/CustomizationManager( 4447):  All configurations done spent 0.097 (s)
W/HtcNativeFlag( 4447): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4447): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4447): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4447): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4447
D/PMS     (  907): acquireHCC(423e9e08): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(423c55c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x6cd5a378 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1108700208
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b11ba0
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  907): acquireWL(4222b420): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4458 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 4458): Copying FileAsset 0x5c7759d8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4458): Binding Chromium to main looper Looper (main, tid 1) {41af6710}
I/LibraryLoader( 4458): Expected native library version number "",actual native library version number ""
I/chromium( 4458): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4458): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(42431578): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): acquireWL(4214a518): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422b8ec8:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4458): 1102102856: getState(). Returning 12
D/PMS     (  907): releaseWL(42431578): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4458): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4458): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4458): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4458): Local Branch: 
I/Adreno-EGL( 4458): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4458): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4458):                  aa63bbd948f41d15fc72f585e
W/chromium( 4458): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4458): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4458): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4458): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4458): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4458): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4458): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4458): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4458): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4458): CordovaWebView is running on device made by: HTC
,W/AwContents( 4458): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +294ms
I/InputMethodManagerService(  907): Disable input method client, pid=1272
I/InputMethodManagerService(  907): Enable input method client, pid=4458
W/ResourceType( 4458): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4458): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b3d7f8, mServedView=org.apache.cordova.engine.SystemWebView{41b03460 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 4458): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  907): releaseWL(4222b420): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4458): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4458): JniHelper::setJavaVM(0x415cc048), pthread_self() = 1663496552
D/JX-Cordova( 4458): jxcore cordova android initializing
,I/dalvikvm-heap( 4458): Grow heap (frag case) to 11.994MB for 42652-byte allocation
,D/PMS     (  907): acquireWL(4250be70): PARTIAL_WAKE_LOCK  Icing 0x1 2230 10028 null
,D/PMS     (  907): releaseWL(4250be70): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4458): Grow heap (frag case) to 12.084MB for 95956-byte allocation
D/PMS     (  907): acquireWL(420e3e70): PARTIAL_WAKE_LOCK  Icing 0x1 2230 10028 null
,D/PMS     (  907): releaseWL(420e3e70): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425dbe70): PARTIAL_WAKE_LOCK  Icing 0x1 2230 10028 null
,D/PMS     (  907): releaseWL(425dbe70): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/dalvikvm-heap( 4458): Grow heap (frag case) to 12.154MB for 143930-byte allocation
,D/PMS     (  907): acquireWL(42128f00): PARTIAL_WAKE_LOCK  Icing 0x1 2230 10028 null
,D/PMS     (  907): releaseWL(42128f00): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4458): Grow heap (frag case) to 12.265MB for 215890-byte allocation
,I/dalvikvm-heap( 4458): Grow heap (frag case) to 12.440MB for 323830-byte allocation
,I/dalvikvm-heap( 4458): Grow heap (frag case) to 12.712MB for 485740-byte allocation
,I/dalvikvm-heap( 4458): Grow heap (frag case) to 13.702MB for 1092904-byte allocation
,I/dalvikvm-heap( 4458): Grow heap (frag case) to 14.632MB for 1639352-byte allocation
,I/dalvikvm-heap( 4458): Grow heap (frag case) to 15.929MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(423e9e08): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(423c55c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4458): Grow heap (frag case) to 18.067MB for 3688532-byte allocation
,W/jxcore-log( 4458): Initializing JXcore engine
,W/jxcore-log( 4458): JXcore engine is ready
,W/jxcore-log( 4458): Starting JXcore engine
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 76
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4506 uid=10077 gids={50077}
,D/PMS     (  907): acquireWL(42e92af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
V/AlarmManager(  907): sending alarm PendingIntent{423f6b98: PendingIntentRecord{423eaf70 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453032800879, Int=60000
,D/PMS     (  907): releaseWL(42e92af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4506): SMSBackupAgentService started
,D/SMSBackup( 4506): Checking restore status
D/SMSBackup( 4506): Restore complete
D/SMSBackup( 4506): cancelCheckAlarm
W/jxcore-log( 4458): Platform android
W/jxcore-log( 4458): 
,W/jxcore-log( 4458): Process ARCH arm
W/jxcore-log( 4458): 
,D/SMSBackup( 4506): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  907): killProcessQuiet, pid=3234
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3234:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3234
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(4214a518): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 4458): JXcore Cordova bridge is ready!
I/jxcore-log( 4458): 
,W/jxcore-log( 4458): JXcore engine is started
,I/chromium( 4458): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4458): Toggling radios to true
I/jxcore-log( 4458): 
,D/BluetoothAdapter( 4458): enable(): BT is already enabled..!
,D/WifiManager( 4458): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1102
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4458, uid=10189
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
D/WifiManager( 4458): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
D/WifiManager( 4458): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): TDLS: Tear down peers
I/wpa_supplicant( 1158): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4458): Radios toggled
I/jxcore-log( 4458): 
I/jxcore-log( 4458): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4458): 
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 48,
I/wpa_supplicant( 1158): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1158): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1158): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412,
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1158): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8681bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1158):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1158): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1158): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1158): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1158): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1158): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=,0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1158): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1158): Wireless event: cmd=0x8b15 len=20
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  907): acquireWL(4239f3e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19551 mDataStallAlarmIntent=PendingIntent{423fbfd8: PendingIntentRecord{424dd968 android broadcastIntent}}
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): Fast associate: Old scan results
I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  907): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1817/10178)
,D/WISPrService( 4212): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WISPrService( 4212): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiService(  907): New client listening to asynchronous messages
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(43723a40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/PMS     (  907): acquireWL(42598530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/PMS     (  907): releaseWL(42598530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1817/10178)
,D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/libc    (  364): [NET] entry_id:6   entry:0xb7dd8410  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7dd80f8  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7dd87c8  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7dd8718  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7dd8548  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb7dd82e0  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb7dd8610  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7dd84b0  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb7dd81c0  removed 
D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/WISPrService( 4212): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4212): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1366/10028)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  907): releaseWL(43723a40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SCAN
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  907): acquireWL(4259c9c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
,D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  907):    returned false
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  907): releaseWL(4259c9c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1458/10028)
D/PMS     (  907): acquireWL(433a4e20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1870/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4348/10100)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3916/10154)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/NetworkMonitor( 3916): type=WIFI subType= reason=null isConnected=false
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1817/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4348/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2482/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4528 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4528): ACRA is enabled for com.facebook.katana, intializing...
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,D/PMS     (  907): releaseWL(433a4e20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ACRA    ( 4528): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4528): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4528): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4528): Preparing secondary program dexes.
V/DexLibLoader( 4528): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4528): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4528): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4528): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4528): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4528): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4528): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4528): Dex already copied
D/OdexVerifier( 4528): Odex verification is skipped.
,V/DexLibLoader( 4528): Creating class loader
,V/DexLibLoader( 4528): Finished creating class loader
V/DexLibLoader( 4528): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4528): Dex already copied
D/OdexVerifier( 4528): Odex verification is skipped.
,V/DexLibLoader( 4528): Creating class loader,
V/DexLibLoader( 4528): Finished creating class loader
V/DexLibLoader( 4528): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4528): Dex already copied
D/OdexVerifier( 4528): Odex verification is skipped.
,V/DexLibLoader( 4528): Creating class loader,
V/DexLibLoader( 4528): Finished creating class loader
V/DexLibLoader( 4528): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar,
V/DexLibLoader( 4528): Dex already copied
D/OdexVerifier( 4528): Odex verification is skipped.
,V/DexLibLoader( 4528): Creating class loader
,V/DexLibLoader( 4528): Finished creating class loader
,V/DexLibLoader( 4528): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4528): DexLibLoader.ensureDexLoaded took 17 ms
,W/dalvikvm( 4528): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
D/wpa_supplicant( 1158): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1158): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1158): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1158): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1158): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 3
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 1
I/wpa_supplicant( 1158): wpa_s->is_screen_on 1
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): selected network = 1
D/wpa_supplicant( 1158): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb86834e8  current_ssid=0x0
D/wpa_supplicant( 1158): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): supplicant attached completed, trigg,er assoc.
D/wpa_supplicant( 1158): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1158): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1158): check if in concurrent case
I/wpa_supplicant( 1158): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1158): RSN: PMKSA cache search - network_ctx=0xb86834e8 try_opportunistic=0
D/wpa_supplicant( 1158): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1158): RSN: No PMKSA cache entry found
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
I/wpa_supplicant( 1158): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1158): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1158): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1158): nl80211: Unsubscribe mgmt frames handle 0xb8682718 (mode change)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1158): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8682718
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb8682718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb8682718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb8682718
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb8682718
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb8682718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb8682718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb8682718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb8682718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb8682718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb8682718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1158):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1158):   * freq=2412
D/wpa_supplicant( 1158):   * Auth Type 0
D/wpa_supplicant( 1158):   * WPA Versions 0x2
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1158): nl80211: Connect request send successfully
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_,supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1158): reply (618) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-49
I/wpa_supplicant( 1158): tsf=0000000107351294
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000107351312
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000107351316
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000107351307
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000107351320
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 107351294, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 107351312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 107351316, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107351307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2462, timestamp: 107351320, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,E/FbInjectorInitializer( 4528): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1158): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1158): nl80211: Connect event
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1158): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1158): Add randomness: count=11 entropy=5
I/wpa_supplicant( 1158): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1158): TDLS: Remove peers on association
D/wpa_supplicant( 1158): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1158): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1158): EAPOL: enable timer tick
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1158): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1158): Get randomness: len=32 entropy=6
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412,
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
,I/wpa_supplicant( 1158): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb86829f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1158):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=1
,I/wpa_supplicant( 1158): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f29b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1158):    broadcast key
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1158): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1158): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1158): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1158): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1158): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=6
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1158): set send_ind_to_ndc = 0
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1158): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1158): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1158): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48,
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1158): EAPOL authentication completed successfully
I/wpa_supplicant( 1158): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WISPrService( 4212): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4212): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
,W/fb4a(:<default>):StaticBindingVerifier( 4528): Verify
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 1
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(431ed088): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424b4560 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424b4560 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4528): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4528): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=4284
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4284:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  907): acquireWL(43603420): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2230 10028 null
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4284
,D/WifiService(  907): Client connection lost with reason: 4
,D/PMS     (  907): acquireWL(43e9c820): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2230 10028 null
,D/PMS     (  907): releaseWL(43603420): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2230/10028)
,D/PMS     (  907): releaseWL(43e9c820): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1366): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2230/10028)
,D/AutoSetting( 1399): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4557 uid=10078 gids={50078, 3003, 5012}
,D/AutoSetting( 1399): Util - no network available!
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
,D/AutoSetting( 1399): service - onCreate()
,D/AutoSetting( 1399): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  907): request 423ff1a0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1399): service - mHandler: cancel location update
,D/AutoSetting( 1399): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4528): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4528): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4528): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4557): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4557): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4557): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4557): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4573 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4557/10078)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4557/10078)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4528): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4557/10078)
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/dalvikvm( 4528): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4528): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4528): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4528): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4528): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4528): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4528): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4528): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4528): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4528): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4528): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4528): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4528): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4528): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4528): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4528): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4528): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4528): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/Process (  907): killProcessQuiet, pid=3875
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4590 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 3875:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 9.908MB for 39954-byte allocation
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 9.984MB for 79892-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4590): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/ActivityManager(  907): Recipient 3875
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 10.049MB for 84664-byte allocation
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1158): Change stage from stage0 to stage3
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  907): releaseWL(431ed088): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4590/10151)
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1158): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19553 delay=15s
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,V/WebViewChromiumFactoryProvider( 4590): Binding Chromium to main looper Looper (main, tid 1) {41afb3c0}
,I/LibraryLoader( 4590): Expected native library version number "",actual native library version number ""
,I/chromium( 4590): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/BrowserStartupController( 4590): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(433ff6b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/WISPrService( 4212): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/AudioManagerAndroid( 4590): BLUETOOTH permission is missing!
,D/WifiWatchdogStateMachine(  907): WAN detection
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/PMS     (  907): acquireWL(435ef220): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): releaseWL(433ff6b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 10.272MB for 75760-byte allocation
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1116): WifiActivity: 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,I/Adreno-EGL( 4590): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4590): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4590): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4590): Local Branch: 
I/Adreno-EGL( 4590): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4590): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4590):                  aa63bbd948f41d15fc72f585e
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@42424c00
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424f0f18 u0 ReceiverList{44279c80 4528 com.facebook.katana/10026/u0 remote:43d17558}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424f0f18 u0 ReceiverList{44279c80 4528 com.facebook.katana/10026/u0 remote:43d17558}}
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437fbad0 u0 ReceiverList{43769e30 4528 com.facebook.katana/10026/u0 remote:43761060}}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/PMS     (  907): acquireWL(44222348): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4557/10078)
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I/NSApplication( 4590): Starting up...
D/PMS     (  907): acquireWL(43752278): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2230 10028 null
D/PMS     (  907): acquireWL(43deb788): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2230 10028 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43752278): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4590/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2230/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4590/10151)
,I/CheckinService( 2230): Preparing to send checkin request
,I/EventLogService( 2230): Accumulating logs since 1453032751950
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/PMS     (  907): acquireWL(438eb688): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1458 10028 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(438eb688): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  907): releaseWL(44222348): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
,D/Process (  907): killProcessQuiet, pid=4039
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/GoogleHttpClient( 2230): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2230): Using GMS GoogleHttpClient
I/ActivityManager(  907): Killing 4039:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1817/10178)
,D/GCoreFlp( 1458): Unknown pending intent to remove.
D/PMS     (  907): acquireWL(43df3720): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1458 10028 null
D/PMS     (  907): releaseWL(43df3720): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1817/10178)
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2230/10028)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (2230/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1817/10178)
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2230): awaiting user notification for token
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41bbade0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 0 8 4 12
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4039
,D/wpa_supplicant( 1158): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1158): EAPOL: disable timer tick
,I/jxcore-log( 4458): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4458): 
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4665 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/jxcore-log( 4458): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4458): 
,I/MultiDex( 4665): install
,I/MultiDex( 4665): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4665): loading existing secondary dex files
,I/MultiDex( 4665): load found 1 secondary dex files
,I/MultiDex( 4665): install done
,I/ProviderInstaller( 4665): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/jxcore-log( 4458): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4458): 
,I/jxcore-log( 4458): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4458): 
,I/jxcore-log( 4458): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4458): 
,I/jxcore-log( 4458): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4458): 
,W/Settings( 4665): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,I/SensorManager(  907): mEventCount = 900
,I/jxcore-log( 4458): Test app app.js loaded
I/jxcore-log( 4458): 
,I/Choreographer( 4458): Skipped 253 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4458): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PMS     (  907): releaseWL(4239f3e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(440d2d70): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(440d2d70): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/NetworkMonitor( 3916): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1870): Checking Certificates
,I/acms    ( 1870): Checking Developer Certificates
I/acms    ( 1870): Checking Application Certificates
I/acms    ( 1870): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1870): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
,I/acms    ( 1870): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1870): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1870): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1870): Updating next query delay: 75600000
I/mlserverapp( 1870): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1870): cancelACMSProgrammedChecks
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3916/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4348/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1870/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1458/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1817/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4557/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4348/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3950/10051)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  907): NoActiveNetworkState
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1458/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(435fe958): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2482/10021)
,D/PMS     (  907): acquireWL(424e2dd0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  907): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4690 uid=10106 gids={50106, 3003, 5012}
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
D/PMS     (  907): releaseWL(435fe958): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4528): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4528): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/PMS     (  907): acquireWL(42416f20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2230 10028 null
,D/PMS     (  907): releaseWL(42416f20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4665/10028)
,D/GCM     ( 1366): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
,D/PMS     (  907): acquireWL(425a6b80): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1366 10028 null
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1366): [NET] getaddrinfo-,err=8
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1366): [NET] getaddrinfo-, 1
D/libc    ( 1366): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c1b4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2230/10028)
,D/AutoSetting( 1399): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4557): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4557): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
,D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1399): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1399): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1399): service - handleMessage() setting current location null
D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1399): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4590/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1817/10178)
I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 219
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1366): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
,I/NewsWeather( 4690): LocationClient connecting
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,I/NewsWeather( 4690): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4690): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4690): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4690): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4690): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4690): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1366): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  907): acquireWL(4209e870): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/PMS     (  907): releaseWL(4209e870): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/CheckinTask( 2230): Sending checkin request (8968 bytes)
D/libc    ( 2230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2230): [NET] getaddrinfo-,err=8
D/libc    ( 2230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2230): [NET] getaddrinfo-, 1
,D/libc    ( 2230): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8cdd +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/ProviderInstaller( 4690): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(423d4e00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,I/NewsWeather( 4690): Last usage 0, idle 1453032806s, sync interval 2592000s
,I/NewsWeather( 4690): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4690): onConnected null
D/PMS     (  907): releaseWL(423d4e00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GCoreFlp( 1458): No location to return for getLastLocation()
,I/NewsWeather( 4690): LocationClient onConnected: location null
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 249
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2230): [NET] getaddrinfo_proxy-, success
D/PMS     (  907): acquireWL(42630488): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1458 10028 null
D/PMS     (  907): acquireWL(4244e5d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1458 10028 null
D/PMS     (  907): releaseWL(42630488): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): releaseWL(4244e5d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4690): Skip sync for lookup editions
,I/NewsWeather( 4690): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4690): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
D/libc    ( 2230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2230): [NET] getaddrinfo-,err=8
,D/GCM     ( 1366): Connected
D/PMS     (  907): acquireWL(4239f0c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  907): releaseWL(425a6b80): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  907): releaseWL(4239f0c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): acquireWL(42598460): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
,D/GCM     ( 1366): Message class mpf
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  907): releaseWL(42598460): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): acquireWL(4342f508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/PMS     (  907): releaseWL(4342f508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4690): Unrecoverable authentication exception
E/NewsWeather( 4690): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4690): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4690): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4690): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c3f560 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4690): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4690): [NET] getaddrinfo-,err=8
D/libc    ( 4690): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4690): [NET] getaddrinfo-, 1
,D/libc    ( 4690): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =996 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 8 3 12
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=70
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4690): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4690): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4690): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(441b07a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/PMS     (  907): releaseWL(441b07a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4690): Failed to syncNewsAppData
,E/NewsWeather( 4690): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43ce2dd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(424e2dd0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 67792, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/Process (  907): killProcessQuiet, pid=4317
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): acquireWL(44199658): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
I/ActivityManager(  907): Killing 4317:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/PMS     (  907): releaseWL(44199658): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  907): releaseWL(43ce2dd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1458/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(425a34e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(425a34e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  907): Recipient 4317
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=3 [31][1][0]
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2230/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (2230/10028)
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
I/RemoteViews( 1116): com.google.android.gms (false,0)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
W/CheckinRequestBuilder( 2230): awaiting user notification for token
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e12850 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1116): com.google.android.gms 0 8 2 12
,I/CheckinTask( 2230): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2230): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2230/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2230/10028)
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  907): releaseWL(43deb788): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2230): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b64020 that was originally bound here
E/ActivityThread( 2230): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b64020 that was originally bound here
E/ActivityThread( 2230): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2230): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2230): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2230): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2230): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2230): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2230): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2230): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2230): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2230): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2230): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2230): 	at bks.a(SourceFile:298)
E/ActivityThread( 2230): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2230): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2230): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1366): GCM config loaded
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,W/fb4a(:<default>):UserScope( 4528): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4528): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-57 , oldRssi= -200
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420bccb0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420bccb0, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42144e08
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@41b06400
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 380ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
,E/fb4a(:<default>):LocalFbBroadcastManager( 4528): Called registerBroadcastReceiver twice.
I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@436fcef8)
D/NfcService( 1258): ScreenObserver: OFF
,D/NfcService( 1258): applyRouting - 0
W/ResourceType( 4458): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4458): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b03460 VFEDH.C. .F...... 0,0-720,1134 #64}
D/HABCtrl (  907): TPE algorithm. remove timeout.
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/PMS     (  907): OOBE c monitor 11
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=4458
D/PMN     (  907): wakingUp
,D/PMS     (  907): acquireWL(43956420): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/NfcService( 1258): applyRouting -2
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
I/WindowManager(  907): No lock screen! windowToken=null
D/PMS     (  907): releaseWL(43956420): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  907): onScreenOn
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  907): acquireWL(441d5978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(441d5978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19554 delay=15s
D/MtpService( 2482): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NfcService( 1258): applyRouting - 0
,D/NfcService( 1258): applyRouting -2
,D/MtpService( 2482): [MTP][onReceive]-
D/PMS     (  907): acquireWL(4336f000): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
,D/PMS     (  907): releaseWL(4336f000): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/ClockThread( 1116): stop update clock
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): SET_SCREEN_ON:On
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1158): BG scan when screen On
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): Match BG scan, scan!
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  907):    returned true
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4733 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/NetworkPolicy(  907): updateScreenOn: false
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d5ed +++++,
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/PMS     (  907): releaseWL(435ef220): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
W/ContextImpl( 4733): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): onScreenOn: 1453032808027
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1777): onScreenOn: 1453032808027
D/PMS     (  907): acquireWL(4426b6d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1458 10028 null
D/PMS     (  907): releaseWL(4426b6d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  907): acquireWL(42e9dfc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4733 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/SmartSyncUtils( 4733): isEpsOn(), nState = 0
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42144e08
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42144e08, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@41b06400
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(42d0c918): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/PMS     (  907): releaseWL(42e9dfc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  907): releaseWL(42d0c918): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19554 mDataStallAlarmIntent=PendingIntent{43e87be0: PendingIntentRecord{424dd968 android broadcastIntent}}
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): SET_SCREEN_ON:Off
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1158): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4733): getMobilePolicyEnabled, result = true
D/PMS     (  907): acquireWL(42ea1918): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/AutoSetting( 1399): receiver - intent: android.intent.action.USER_PRESENT
,D/Process (  907): killProcessQuiet, pid=4348
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(42ea1918): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/ActivityManager(  907): Killing 4348:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/NetworkPolicy(  907): updateScreenOn: false
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/TetherSettings( 4212): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4212): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4212): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4212): Cust_ConnectToPC   : spcsc>false
D/        ( 4212): Cust_ConnectToPC   : IPT>true
D/        ( 4212): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4212): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
E/SmartNS_Utility( 4212): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4212): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4212): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,I/PSReceiver( 4212): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4212): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4212): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4212):  defaultType:0
W/ContextImpl( 4212): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4733): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4733): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4733): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4733): isEpsOn(), nState = 0
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41b06400
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
D/WifiService(  907): New client listening to asynchronous messages
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41b06400, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41b06400, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/ContactMessageStore( 1242): start background delete task...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41b06400
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4348
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4232b3b8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4232b3b8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1777): onScreenOff
D/PMS     (  907): acquireWL(426654e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1458 10028 null
,D/PMS     (  907): releaseWL(426654e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1399): service - mHandler: cancel location update
D/AutoSetting( 1399): service -           changes count: 0
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4590): Thread[GAThread,5,main]: No campaign data found.
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-86
D/wpa_supplicant( 1158): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=12 entropy=0
D/wpa_supplicant( 1158): Add randomness: count=13 entropy=1
D/wpa_supplicant( 1158): Add randomness: count=14 entropy=2
D/wpa_supplicant( 1158): Add randomness: count=15 entropy=3
D/wpa_supplicant( 1158): Add randomness: count=16 entropy=4
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1158): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
E/wpa_sup,plicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-86
D/wpa_supplicant( 1158): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=17 entropy=5
D/wpa_supplicant( 1158): Add randomness: count=18 entropy=6
D/wpa_supplicant( 1158): Add randomness: count=19 entropy=7
D/wpa_supplicant( 1158): Add randomness: count=20 entropy=8
D/wpa_supplicant( 1158): Add randomness: count=21 entropy=9
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
,D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1158): State: DISCONNECTED -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1158): reply (618) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-49
I/wpa_supplicant( 1158): tsf=0000000114111971
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-58
I/wpa_supplicant( 1158): tsf=0000000114112007
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000107351316
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000107351307
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
,I/wpa_supplicant( 1158): level=-86
I/wpa_supplicant( 1158): tsf=0000000114112027
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@437e7e00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@437e7e00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@437e7e00 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 114111971, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 114112007, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 107351316, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107351307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -86, frequency: 2462, timestamp: 114112027, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-86], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==,
,D/WifiStateMachine(  907): == (5) end of scan result ==,
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/GAV4    ( 4690): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  907): killProcessQuiet, pid=4364
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4364:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4364
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1491): service - handleMessage() stop self
,D/AutoSetting( 1491): service - onDestroy() END
,D/AutoSetting( 1491): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4335
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4335:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4335
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 10.944MB for 18476-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 10.958MB for 27710-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 10.981MB for 41560-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 11.013MB for 62336-byte allocation
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 11.058MB for 66154-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 11.058MB for 44222-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 11.090MB for 57356-byte allocation
,D/libc    ( 4528): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4528): [NET] getaddrinfo-,err=8
D/libc    ( 4528): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4528): [NET] getaddrinfo-, 1
,D/libc    ( 4528): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =37dc +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 42
D/libc    (  364): [NET]res_nsend:resplen=93
D/libc    (  364): [NET]res_queryN: exit 3, ancount=3
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4528): [NET] getaddrinfo_proxy-, success
,I/global  ( 4528): call createSocket() return a new socket.
D/libc    ( 4528): [NET] getaddrinfo+,hn 13(0x3137392e36302e),sn(),family 0,flags 4
,D/libc    ( 4528): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4528): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4528): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(435e7408): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4528 10026 null
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 11.178MB for 65534-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4528/10026)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/global  ( 4528): I/O error closing connection
I/global  ( 4528): java.net.SocketException: Socket is closed
I/global  ( 4528): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4528): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4528): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4528): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4528): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4528): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4528): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4528): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4528): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4528): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4528): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4528): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4528): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4528): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4528): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4528): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4528): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4528): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4528): Removing a connection that never existed!
D/PMS     (  907): releaseWL(435e7408): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{431d5958 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
,D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-82
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=22 entropy=10
D/wpa_supplicant( 1158): Add randomness: count=23 entropy=11
D/wpa_supplicant( 1158): Add randomness: count=24 entropy=12
D/wpa_supplicant( 1158): Add randomness: count=25 entropy=13
D/wpa_supplicant( 1158): Add randomness: count=26 entropy=14
D/wpa_supplicant( 1158): Add randomness: count=27 entropy=15
D/wpa_supplicant( 1158): Add randomness: count=28 entropy=16
D/wpa_supplicant( 1158): Add randomness: count=29 entropy=17
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplica,nt( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1158): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 5: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 6: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 7: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-82
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=30 entropy=18
D/wpa_supplicant( 1158): Add randomness: count=31 entropy=19
D/wpa_supplicant( 1158): Add randomness: count=32 entropy=20
D/wpa_supplicant( 1158): Add randomness: count=33 entropy=21
D/wpa_supplicant( 1158): Add randomness: count=34 entropy=22
D/wpa_supplicant( 1158): Add randomness: count=35 entropy=23
D/wpa_supplicant( 1158): Add randomness: count=36 entropy=24
D/wpa_supplicant( 1158): Add randomness: count=37 entropy=25
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: AP dc:4a:3e:0f:c2,:f1 type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1158): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1158): reply (1053) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-49
I/wpa_supplicant( 1158): tsf=0000000131504405
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-58
I/wpa_supplicant( 1158): tsf=0000000131504444
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000131504454
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000107351307
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-87
I/wpa_,supplicant( 1158): tsf=0000000131504496
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=5
I/wpa_supplicant( 1158): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-82
I/wpa_supplicant( 1158): tsf=0000000131504463
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=6
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000131504484
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=7
I/wpa_supplicant( 1158): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-90
I/wpa_supplicant( 1158): tsf=0000000131504474
I/wpa_supplicant( 1158): flags=[WPA-EAP-CC
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 131504405, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 131504444, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 131504454, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107351307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2462, timestamp: 131504496, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
D/WifiStateMachine(  907): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -82, frequency: 2437, timestamp: 131504463, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 131504484, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 131504474, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 8 to mScanResults
D/PMS     (  907): acquireWL(432ddf98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(432ddf98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-87], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  74, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  6 [-82], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  68, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (8) end of scan result ==
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(425b1058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/PMS     (  907): acquireWL(425213e8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{41d4e6b8: PendingIntentRecord{42497498 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=132561, Int=0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(425b1058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42104548): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(425213e8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42104548): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1399): service - mHandler: update timezone
,D/AutoSetting( 1491): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1491): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1491): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1491): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1491): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1567): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1491): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1491): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1491): service - mHandler: update timezone
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1491): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1491): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1491): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1491): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41eaff78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 8 2 11
,D/AutoSetting( 1399): service - handleMessage() stop self
,D/AutoSetting( 1399): service - handleMessage() quit looper
,D/AutoSetting( 1399): service - onDestroy() END
,D/PMS     (  907): acquireWL(42307df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421ec838: PendingIntentRecord{4237dcc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=143237, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42307df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
,D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  907): killProcessQuiet, pid=3950
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3950:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3950
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=38 entropy=26
D/wpa_supplicant( 1158): Add randomness: count=39 entropy=27
D/wpa_supplicant( 1158): Add randomness: count=40 entropy=28
D/wpa_supplicant( 1158): Add randomness: count=41 entropy=29
D/wpa_supplicant( 1158): Add randomness: count=42 entropy=30
D/wpa_supplicant( 1158): Add randomness: count=43 entropy=31
D/wpa_supplicant( 1158): Add randomness: count=44 entropy=32
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1158): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 4: 0c:bd:51:2,b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1158): BSS: last_scan_res_used=7/32 last_scan_full=0
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1158): Add randomness: count=45 entropy=33
D/wpa_supplicant( 1158): Add randomness: count=46 entropy=34
D/wpa_supplicant( 1158): Add randomness: count=47 entropy=35
D/wpa_supplicant( 1158): Add randomness: count=48 entropy=36
D/wpa_supplicant( 1158): Add randomness: count=49 entropy=37
D/wpa_supplicant( 1158): Add randomness: count=50 entropy=38
D/wpa_supplicant( 1158): Add randomness: count=51 entropy=39
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
W/wpa_supplicant( 1158): p2p0: Not, restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1158): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1158): reply (1053) for get BSS: id=0,
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-49
I/wpa_supplicant( 1158): tsf=0000000148883889
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412,
I/wpa_supplicant( 1158): level=-58
I/wpa_supplicant( 1158): tsf=0000000148883928
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000148883938
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos,
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000107351307
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25,
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000148883967
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=5
I/wpa_supplicant( 1158): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-82
I/wpa_supplicant( 1158): tsf=0000000131504463
,I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=6
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000131504484
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=7
I/wpa_supplicant( 1158): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-90
I/wpa_supplicant( 1158): tsf=0000000148883948
I/wpa_supplicant( 1158): flags=[WPA-EAP-CC
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiP2pService(  907): InactiveState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 148883889, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 148883928, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 148883938, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107351307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2462, timestamp: 148883967, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -82, frequency: 2437, timestamp: 131504463, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 131504484, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 148883948, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 8 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-87], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  74, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  6 [-82], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  68, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (8) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4376a440 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(425d8ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{424cfdc0: PendingIntentRecord{424cfd60 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141141, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{43752848: PendingIntentRecord{42402f50 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141440, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
V/AlarmManager(  907): sending alarm PendingIntent{41d4e6b8: PendingIntentRecord{42497498 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=162578, Int=0
,D/PMS     (  907): acquireWL(4390e670): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10028)
,D/PMS     (  907): acquireWL(42586ae0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): acquireWL(43d17120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/PMS     (  907): releaseWL(425d8ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): releaseWL(43d17120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c62f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(423d9e60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=4 [89][4][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4,
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/PMS     (  907): acquireWL(423c6a70): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
D/PMS     (  907): releaseWL(42586ae0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  907): releaseWL(423d9e60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42597f98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/NewsWeather( 4690): Last usage 0, idle 1453032859s, sync interval 2592000s
,I/NewsWeather( 4690): setPeriodicSync in seconds 2592000
D/PMS     (  907): releaseWL(42597f98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,I/NewsWeather( 4690): Skip sync for lookup editions
,I/NewsWeather( 4690): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4690): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4690): Unrecoverable authentication exception
E/NewsWeather( 4690): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4690): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4690): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4690): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b3ed88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 12 3 12
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): acquireWL(4321d500): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,E/NewsWeather( 4690): Failed to syncNewsAppData
,E/NewsWeather( 4690): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(4321d500): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42548cd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(423c6a70): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 110082, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(42548cd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42508540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1458/10028)
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  907): releaseWL(42508540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
,D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=52 entropy=40
D/wpa_supplicant( 1158): Add randomness: count=53 entropy=41
D/wpa_supplicant( 1158): Add randomness: count=54 entropy=42
D/wpa_supplicant( 1158): Add randomness: count=55 entropy=43
D/wpa_supplicant( 1158): Add randomness: count=56 entropy=44
D/wpa_supplicant( 1158): Add randomness: count=57 entropy=45
D/wpa_supplicant( 1158): Add randomness: count=58 entropy=46
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1158): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1158): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=7/32 last_scan_full=0
,D/wpa_supplicant( 1158): Add randomness: count=59 entropy=47
D/wpa_supplicant( 1158): Add randomness: count=60 entropy=48
D/wpa_supplicant( 1158): Add randomness: count=61 entropy=49
D/wpa_supplicant( 1158): Add randomness: count=62 entropy=50
D/wpa_supplicant( 1158): Add randomness: count=63 entropy=51
D/wpa_supplicant( 1158): Add randomness: count=64 entropy=52
D/wpa_supplicant( 1158): Add randomness: count=65 entropy=53
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1158): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1158): reply (908) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-49
I/wpa_supplicant( 1158): tsf=0000000166212753
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000166212791
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000166212802
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000107351307
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000166212831
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=6
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000131504484
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=7
I/wpa_supplicant( 1158): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-90
I/wpa_supplicant( 1158): tsf=0000000166212811
I/wpa_supplicant( 1158): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=UPC Wi-Free
I/wpa_supplicant( 1158): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 166212753, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 166212791, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 166212802, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107351307, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2462, timestamp: 166212831, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 131504484, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 166212811, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 7 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-87], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  74, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(4390e670): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1491): service - handleMessage() stop self
,D/AutoSetting( 1491): service - onDestroy() END
,D/AutoSetting( 1491): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4388
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4388:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4388
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42fee558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(42fee558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
,D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1158): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=66 entropy=54
D/wpa_supplicant( 1158): Add randomness: count=67 entropy=55
D/wpa_supplicant( 1158): Add randomness: count=68 entropy=56
D/wpa_supplicant( 1158): Add randomness: count=69 entropy=57
D/wpa_supplicant( 1158): Add randomness: count=70 entropy=58
D/wpa_supplicant( 1158): Add randomness: count=71 entropy=59
D/wpa_supplicant( 1158): Add randomness: count=72 entropy=60
D/wpa_supplicant( 1158): Add randomness: count=73 entropy=61
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1158): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1,158): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 7: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1158): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=74 entropy=62
D/wpa_supplicant( 1158): Add randomness: count=75 entropy=63
D/wpa_supplicant( 1158): Add randomness: count=76 entropy=64
D/wpa_supplicant( 1158): Add randomness: count=77 entropy=65
D/wpa_supplicant( 1158): Add randomness: count=78 entropy=66
D/wpa_supplicant( 1158): Add randomness: count=79 entropy=67
D/wpa_supplicant( 1158): Add randomness: count=80 entropy=68
D/wpa_supplicant( 1158): Add randomness: count=81 entropy=69
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): p2p0: Not restrict, scheduled scan for Not WFD CT3
I/wpa_supplicant( 1158): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1158): reply (1021) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-48
I/wpa_supplicant( 1158): tsf=0000000166212753
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000183654444
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000183654455
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000107351307
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000183654495
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=6
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000183654485
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=7
I/wpa_supplicant( 1158): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-89
I/wpa_supplicant( 1158): tsf=0000000183654464
I/wpa_supplicant( 1158): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=UPC Wi-Free
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=8
I/wpa_supplicant( 1158): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-90
I/wpa_supplicant( 1158): tsf=0000000183654474
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCM
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 166212753, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 183654444, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 183654455, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107351307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 183654495, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 183654485, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 183654464, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -90, frequency: 2412, timestamp: 183654474, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 8 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  74, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  74, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-90], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (8) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(435ff590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(435ff590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43dc00e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41d4e6b8: PendingIntentRecord{42497498 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=192675, Int=0
,D/PMS     (  907): acquireWL(43e29f38): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(43dc00e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42eaa400): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43e29f38): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42eaa400): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
,D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
I/wpa_supplicant( 1158): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=82 entropy=70
D/wpa_supplicant( 1158): Add randomness: count=83 entropy=71
D/wpa_supplicant( 1158): Add randomness: count=84 entropy=72
D/wpa_supplicant( 1158): Add randomness: count=85 entropy=73
D/wpa_supplicant( 1158): Add randomness: count=86 entropy=74
D/wpa_supplicant( 1158): Add randomness: count=87 entropy=75
D/wpa_supplicant( 1158): Add randomness: count=88 entropy=76
D/wpa_supplicant( 1158): Add randomness: count=89 entropy=77
D/wpa_supplicant( 1158): Add randomness: count=90 entropy=78
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): ,wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1158): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 6: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 7: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 8: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
I/wpa_supplicant( 1158): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=91 entropy=79
D/wpa_supplicant( 1158): Add randomness: count=92 entropy=80
D/wpa_supplicant( 1158): Add randomness: count=93 entropy=81
D/wpa_supplicant( 1158): Add randomness: count=94 entropy=82
D/wpa_supplicant( 1158): Add randomness: count=95 entropy=83
D/wpa_supplicant( 1158): Add randomness: count=96 entropy=84
D/wpa_supplicant( 1158): Add randomness: count=97 entropy=85
D/wpa_supplicant( 1158): Add randomness: count=98 entropy=86
D/wpa_supplicant( 1158): Add randomness: count=99 entropy=87
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
,W/wpa_supplicant( 1158): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1158): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1158): reply (1166) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-48
I/wpa_supplicant( 1158): tsf=0000000201114287
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000201114326
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000201114336
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000107351307
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
,I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000201114386
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=6
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000201114366
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=7
I/wpa_supplicant( 1158): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000201114356
I/wpa_supplicant( 1158): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=UPC Wi-Free
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=8
I/wpa_supplicant( 1158): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-90
,I/wpa_supplicant( 1158): tsf=0000000201114346
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCM
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 201114287, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 201114326, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 201114336, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107351307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2462, timestamp: 201114386, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 201114366, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 201114356, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 7: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -90, frequency: 2412, timestamp: 201114346, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 201114375, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-87], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-90], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43543380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421ec838: PendingIntentRecord{4237dcc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=203237, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43543380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
,D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=100 entropy=88
D/wpa_supplicant( 1158): Add randomness: count=101 entropy=89
D/wpa_supplicant( 1158): Add randomness: count=102 entropy=90
D/wpa_supplicant( 1158): Add randomness: count=103 entropy=91
D/wpa_supplicant( 1158): Add randomness: count=104 entropy=92
D/wpa_supplicant( 1158): Add randomness: count=105 entropy=93
D/wpa_supplicant( 1158): Add randomness: count=106 entropy=94
D/wpa_supplicant( 1158): Add randomness: count=107 entropy=95
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SELECT_BSSID CM,D...
D/wpa_supplicant( 1158): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 6: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 7: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-90
D/wpa_supplicant( 1158): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=108 entropy=96
D/wpa_supplicant( 1158): Add randomness: count=109 entropy=97
D/wpa_supplicant( 1158): Add randomness: count=110 entropy=98
D/wpa_supplicant( 1158): Add randomness: count=111 entropy=99
D/wpa_supplicant( 1158): Add randomness: count=112 entropy=100
D/wpa_supplicant( 1158): Add randomness: count=113 entropy=101
D/wpa_supplicant( 1158): Add randomness: count=114 entropy=102
D/wpa_supplicant( 1158): Add randomness: count=115 entropy=103
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
,W/wpa_supplicant( 1158): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1158): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1158): reply (1166) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-48
I/wpa_supplicant( 1158): tsf=0000000218584977
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000218585004
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000218585015
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-57
I/wpa_supplicant( 1158): tsf=0000000107351307
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000218585065
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=6
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000218585045
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=7
I/wpa_supplicant( 1158): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000218585035
I/wpa_supplicant( 1158): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=UPC Wi-Free
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=8
I/wpa_supplicant( 1158): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-90
I/wpa_supplicant( 1158): tsf=0000000218585025
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCM
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 218584977, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 218585004, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 218585015, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107351307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2462, timestamp: 218585065, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 218585045, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 218585035, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -90, frequency: 2412, timestamp: 218585025, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 218585054, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-87], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-90], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(430180d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41d4e6b8: PendingIntentRecord{42497498 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=226954, Int=0
,D/PMS     (  907): acquireWL(441fb4c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(430180d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(435e44b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=1 [56][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
,D/PMS     (  907): acquireWL(425f65a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(441fb4c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(435e44b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43e3bfb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43e3bfb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4690): Last usage 0, idle 1453032923s, sync interval 2592000s
I/NewsWeather( 4690): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4690): Skip sync for lookup editions
,I/NewsWeather( 4690): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4690): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4690): Unrecoverable authentication exception
E/NewsWeather( 4690): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4690): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4690): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4690): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4690): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b17dc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 5 13 4 12
,D/PMS     (  907): acquireWL(4371aa40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
E/NewsWeather( 4690): Failed to syncNewsAppData
,E/NewsWeather( 4690): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(4371aa40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(436b18d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 163171, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(425f65a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(436b18d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(433c3e00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1458/10028)
D/PMS     (  907): releaseWL(433c3e00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(4422d280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{42f960f8: PendingIntentRecord{4389f240 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228275, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4784 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{4257a908: PendingIntentRecord{42519250 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453032917569, Int=10800000
,D/PMS     (  907): releaseWL(4422d280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4784/10047)
,D/Process (  907): killProcessQuiet, pid=4406
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4406:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4406
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2230/10028)
,D/PMS     (  907): acquireWL(42666970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42666970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43db0300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{438225b8: PendingIntentRecord{4389f240 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231296, Int=0
,D/PMS     (  907): releaseWL(43db0300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
,D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
D/wpa_supplicant( 1158): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=116 entropy=104
D/wpa_supplicant( 1158): Add randomness: count=117 entropy=105
D/wpa_supplicant( 1158): Add randomness: count=118 entropy=106
D/wpa_supplicant( 1158): Add randomness: count=119 entropy=107
D/wpa_supplicant( 1158): Add randomness: count=120 entropy=108
D/wpa_supplicant( 1158): Add randomness: count=121 entropy=109
D/wpa_supplicant( 1158): Add randomness: count=122 entropy=110
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1158,): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 3: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 6: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
D/wpa_supplicant( 1158): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=123 entropy=111
D/wpa_supplicant( 1158): Add randomness: count=124 entropy=112
D/wpa_supplicant( 1158): Add randomness: count=125 entropy=113
D/wpa_supplicant( 1158): Add randomness: count=126 entropy=114
D/wpa_supplicant( 1158): Add randomness: count=127 entropy=115
D/wpa_supplicant( 1158): Add randomness: count=128 entropy=116
D/wpa_supplicant( 1158): Add randomness: count=129 entropy=117
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1158): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1158): reply (1184) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-48
I/wpa_supplicant( 1158): tsf=0000000235894110
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-56
I/wpa_supplicant( 1158): tsf=0000000235894137
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000235894148
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000235894178
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=6
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000218585045
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=7
I/wpa_supplicant( 1158): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000235894158
I/wpa_supplicant( 1158): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=UPC Wi-Free
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id,=8
I/wpa_supplicant( 1158): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-90
I/wpa_supplicant( 1158): tsf=0000000218585025
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=WDA83
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=9
I/wpa_supplicant( 1158): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000218585054
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCM
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  907): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 235894110, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 235894137, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 235894148, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2462, timestamp: 235894178, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 218585045, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 235894158, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 6: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -90, frequency: 2412, timestamp: 218585025, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 7: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 218585054, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 235894188, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 9 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-87], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-90], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  70, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  66, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-91], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
,D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(43e77998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(43e77998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1158): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
I/wpa_supplicant( 1158): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-91
D/wpa_supplicant( 1158): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=130 entropy=118
D/wpa_supplicant( 1158): Add randomness: count=131 entropy=119
D/wpa_supplicant( 1158): Add randomness: count=132 entropy=120
D/wpa_supplicant( 1158): Add randomness: count=133 entropy=121
D/wpa_supplicant( 1158): Add randomness: count=134 entropy=122
D/wpa_supplicant( 1158): Add randomness: count=135 entropy=123
D/wpa_supplicant( 1158): Add randomness: count=136 entropy=124
D/wpa_supplicant( 1158): Add randomness: count=137 entropy=125
D/wpa_supplicant( 1158): Add randomness: count=138 entropy=126
D/wpa_supplicant( 1158): Add randomness: count=139 entropy=127
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP 80:f5:03:a6:74:13 type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[6] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=241,2 rssi=-56
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1158): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 6: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 7: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 8: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1158): 9: 80:f5:03:a6:74:13 ssid='UPC246351350' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1158): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-87,
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1158): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
I/wpa_supplicant( 1158): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-91
D/wpa_supplicant( 1158): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=140 entropy=128
D/wpa_supplicant( 1158): Add randomness: count=141 entropy=129
D/wpa_supplicant( 1158): Add randomness: count=142 entropy=130
D/wpa_supplicant( 1158): Add randomness: count=143 entropy=131
D/wpa_supplicant( 1158): Add randomness: count=144 entropy=132
D/wpa_supplicant( 1158): Add randomness: count=145 entropy=133
D/wpa_supplicant( 1158): Add randomness: count=146 entropy=134
D/wpa_supplicant( 1158): Add randomness: count=147 entropy=135
D/wpa_supplicant( 1158): Add randomness: count=148 entropy=136
D/wpa_supplicant( 1158): Add randomness: count=149 entropy=137
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP 80:f5:03:a6:74:13 type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[6] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 11,58): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1158): reply (1316) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-48
I/wpa_supplicant( 1158): tsf=0000000253294720
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-56
I/wpa_supplicant( 1158): tsf=0000000253294760
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000253294770
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000253294811
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=6
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000253294790
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=7
I/wpa_supplicant( 1158): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000253294780
I/wpa_supplicant( 1158): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=UPC Wi-Free
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=9
I/wpa_supplicant( 1158): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000253294799
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=DIRECT-AD-HP DeskJet 3630 series
I/,wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=10
I/wpa_supplicant( 1158): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-91
I/wpa_supplicant( 1158): tsf=000
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 253294720, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 253294760, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 253294770, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2462, timestamp: 253294811, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 253294790, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 253294780, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 253294799, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 253294820, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 253294748, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 9: scan result = SSID: UPC246351350, BSSID: 80:f5:03:a6:74:13, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 253294830, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 10 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-87], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                     UPC246351350 [80:f5:03:a6:74:13], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  66, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-91], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (10) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44743228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41d4e6b8: PendingIntentRecord{42497498 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=257021, Int=0
,D/PMS     (  907): acquireWL(4429a808): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(44743228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44238030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4429a808): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(44238030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(43c855d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421ec838: PendingIntentRecord{4237dcc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=263236, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c855d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
,D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1158): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
I/wpa_supplicant( 1158): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-91
D/wpa_supplicant( 1158): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=150 entropy=138
D/wpa_supplicant( 1158): Add randomness: count=151 entropy=139
D/wpa_supplicant( 1158): Add randomness: count=152 entropy=140
D/wpa_supplicant( 1158): Add randomness: count=153 entropy=141
D/wpa_supplicant( 1158): Add randomness: count=154 entropy=142
D/wpa_supplicant( 1158): Add randomness: count=155 entropy=143
D/wpa_supplicant( 1158): Add randomness: count=156 entropy=144
D/wpa_supplicant( 1158): Add randomness: count=157 entropy=145
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[6] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a,2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1158): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 5: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 6: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1158): 7: 80:f5:03:a6:74:13 ssid='UPC246351350' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1158): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
I/wpa_supplicant( 1158): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-91
D/wpa_supplicant( 1158): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=158 entropy=146
D/wpa_supplicant( 1158): Add randomness: count=159 entropy=147
D/wpa_supplicant( 1158): Add randomness: count=160 entropy=148
D/wpa_supplicant( 1158): Add randomness: count=161 entropy=149
D/wpa_supplicant( 1158): Add randomness: count=162 entropy=150
D/wpa_supplicant( 1158): Add randomness: count=163 entropy=151
D/wpa_supplicant( 1158): Add randomness: count=164 entropy=152
D/wpa_supplicant( 1158): Add randomness: count=165 entropy=153
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA sube,lement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[6] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1158): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1158): reply (1316) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-48
I/wpa_supplicant( 1158): tsf=0000000270694194
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-56
I/wpa_supplicant( 1158): tsf=0000000270694232
,I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000270694242
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000270694262
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=6
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000270694252
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=7
I/wpa_supplicant( 1158): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000253294780
I/wpa_supplicant( 1158): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=UPC Wi-Free
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=9
I/wpa_supplicant( 1158): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000253294799
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=10
I/wpa_supplicant( 1158): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-91
I/wpa_supplicant( 1158): tsf=000
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 270694194, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 270694232, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 270694242, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 3: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 270694262, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 270694252, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 253294780, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: DIRECT-AD-HP Desk,Jet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 253294799, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 270694272, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 270694221, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 9: scan result = SSID: UPC246351350, BSSID: 80:f5:03:a6:74:13, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 270694282, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 10 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                     UPC246351350 [80:f5:03:a6:74:13], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  66, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-91], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (10) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
,D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-91
D/wpa_supplicant( 1158): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=166 entropy=154
D/wpa_supplicant( 1158): Add randomness: count=167 entropy=155
D/wpa_supplicant( 1158): Add randomness: count=168 entropy=156
D/wpa_supplicant( 1158): Add randomness: count=169 entropy=157
D/wpa_supplicant( 1158): Add randomness: count=170 entropy=158
D/wpa_supplicant( 1158): Add randomness: count=171 entropy=159
D/wpa_supplicant( 1158): Add randomness: count=172 entropy=160
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[6] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 9
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 0
I/wpa_supplicant( 1158): wpa_s->is_screen_on 0
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): Do nothing, wait SE,LECT_BSSID CMD...
D/wpa_supplicant( 1158): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 4: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1158): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1158): 6: 80:f5:03:a6:74:13 ssid='UPC246351350' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1158): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1158): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-88
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1158): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-91
D/wpa_supplicant( 1158): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=173 entropy=161
D/wpa_supplicant( 1158): Add randomness: count=174 entropy=162
D/wpa_supplicant( 1158): Add randomness: count=175 entropy=163
D/wpa_supplicant( 1158): Add randomness: count=176 entropy=164
D/wpa_supplicant( 1158): Add randomness: count=177 entropy=165
D/wpa_supplicant( 1158): Add randomness: count=178 entropy=166
D/wpa_supplicant( 1158): Add randomness: count=179 entropy=167
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[6] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): clear disabled list - type=1
I/wpa_supplicant( 1158): No suitable network found
W/wpa_supplicant( 1158): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1158): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1158): reply (1028) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-48
I/wpa_supplicant( 1158): tsf=0000000288103690
,I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-56
I/wpa_supplicant( 1158): tsf=0000000288103728
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000288103738
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000288103759
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=6
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-88
I/wpa_supplicant( 1158): tsf=0000000288103748
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=10
I/wpa_supplicant( 1158): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-91
I/wpa_supplicant( 1158): tsf=0000000270694272
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC243894600
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=11
I/wpa_su,pplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-56
I/wpa_supplicant( 1158): tsf=0000000288103717
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=12
I/wpa_supplicant( 1158): bssid=80:f5:03:a6:74:13
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-91
I/wpa_supplicant( 1158): tsf=0000000288103769
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP+TKIP][WP
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 288103690, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 288103728, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 288103738, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2462, timestamp: 288103759, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 288103748, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 270694272, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 288103717, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC246351350, BSSID: 80:f5:03:a6:74:13, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 288103769, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 8 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  74, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                     UPC246351350 [80:f5:03:a6:74:13], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-91], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (8) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43c9b1a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43c9b1a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4458): --= Surplus to requirements =--
I/jxcore-log( 4458): 
I/jxcore-log( 4458): ****TEST TOOK:  ms ****
I/jxcore-log( 4458): 
,I/jxcore-log( 4458): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4458): 
,E/cutils-trace( 4808): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4808): ====startRecUseTime====
D/htc.customization.log.level( 4808):  is 
,W/CustomizationLogLevel( 4808): Level value is invalid, use default level 2
,D/CustomizationManager( 4808):  Read ACC file spent 0.093 (s)
D/CIDMapFileReader( 4808): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4808): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4808): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4808): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4808): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4808): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4808): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4808): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4808): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4808): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4808): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4808): Parsing tag category name = system,
,I/CustomizationCIDLoader( 4808): Parsing tag category name = application
I/CustomizationCIDLoader( 4808): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4808): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4808): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4808): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 4808): Parsing tag category name = Settings
D/CustomizationManager( 4808):  Read CID file spent 0.144 (s)
,D/CustomizationManager( 4808):  All configurations done spent 0.144 (s)
,W/HtcNativeFlag( 4808): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4808): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4808): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4808): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4808, uid=2000 user=0
,D/Process (  907): killProcessQuiet, pid=4458
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,I/ActivityManager(  907): Killing 4458:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907):   Force finishing activity ActivityRecord{41b05fa8 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  907): Copying FileAsset 0x6cd488b0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  907): WIN DEATH: Window{42299508 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  907): Client connection lost with reason: 4
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4458 uid 10189
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 15.196MB for 1821008-byte allocation
,D/DotMatrix( 1567): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1567): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/acms    ( 1870): Unregistering com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
E/acms    ( 1870): Could not unregister removed application com.test.thalitest
,W/GeofencerStateMachine( 1458): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(433ce1b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1458 10028 null
D/PMS     (  907): releaseWL(433ce1b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/VoicemailCleanupService( 1298): Cleaning up data for package: com.test.thalitest
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsRemoved
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/PackageBroadcastService( 2230): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4824 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/Parcel  ( 1258): Reading a NULL string not supported here.
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  907):   Scheme: "mmsto"
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/MultiDex( 4824): install
,I/MultiDex( 4824): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  907): Delaying start of: ServiceRecord{4422edb0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/MultiDex( 4824): loading existing secondary dex files
,I/MultiDex( 4824): load found 1 secondary dex files
,I/MultiDex( 4824): install done
,I/PeopleContactsSync( 2230): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2230, uid=10028, userID:0
,D/PMS     (  907): acquireWL(43e6a398): PARTIAL_WAKE_LOCK  Icing 0x1 2230 10028 null
I/Icing   ( 2230): doRemovePackageData com.test.thalitest
,D/PMS     (  907): releaseWL(43e6a398): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4842 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ProviderInstaller( 4824): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4842): install
,I/MultiDex( 4842): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4842): loading existing secondary dex files
,I/MultiDex( 4842): load found 1 secondary dex files
,I/MultiDex( 4842): install done
,I/ActivityManager(  907): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1399): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/ProviderInstaller( 4842): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1399): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=4421
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  907): Killing 4421:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4421
,I/IcingCorporaProvider( 2909): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4861 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/SQLiteLog( 2909): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2909): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x645d8fd0
,W/dalvikvm( 2909): threadid=16: thread exiting with uncaught exception (group=0x416c4e30)
,E/AndroidRuntime( 2909): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2909): Process: com.google.android.googlequicksearchbox:search, PID: 2909
E/AndroidRuntime( 2909): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2909): 	at cid.d(PG:186)
E/AndroidRuntime( 2909): 	at clo.g(PG:594)
E/AndroidRuntime( 2909): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2909): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2909): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2909): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2909): 	at clr.tL(PG:827)
E/AndroidRuntime( 2909): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2909): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2909): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2909): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
,D/Process ( 2909): killProcess, pid=2909
,D/Process ( 2909): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,I/ActivityManager(  907): Recipient 2909
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.google.android.googlequicksearchbox:search (pid 2909) has died.
D/MediaRouterService(  907): Client com.google.android.googlequicksearchbox (pid 2909): Died!
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
,D/WifiService(  907): Client connection lost with reason: 4
,E/SQLiteLog( 4824): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4824): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca26ba8
,E/DriveAsyncService( 4824): disk I/O error (code 3850)
E/DriveAsyncService( 4824): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4824): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4824): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4824): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4824): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4824): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4824): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4824): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4824): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4824): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4824): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4824): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4824): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4824): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4824): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4824): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca26ba8
,E/DocListDatabase( 4824): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4824): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4824): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4824): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4824): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4824): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4824): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4824): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4824): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4824): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4824): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4824): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4824): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4824): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4824): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4824): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4824): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4824): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4824): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4824): threadid=1: thread exiting with uncaught exception (group=0x416c4e30)
,E/AndroidRuntime( 4824): FATAL EXCEPTION: main
E/AndroidRuntime( 4824): Process: com.google.android.gms.drive, PID: 4824
E/AndroidRuntime( 4824): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4824): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4824): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4824): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4824): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4824): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4824): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4824): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4824): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4824): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4824): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4824): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4824): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4824): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4824): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4824): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4824): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4824): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4824): 	... 10 more
,E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
,D/Process ( 4824): killProcess, pid=4824
,D/Process ( 4824): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,I/ActivityManager(  907): Recipient 4824
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4824) has died.
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 10869ms
,E/SQLiteDatabase( 4861): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4861): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4861): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4861): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4861): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4861): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4861): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4861): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4861): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4861): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4861): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4861): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4861): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4861): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4861): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4861): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4861): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4861): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4861): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4861): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4861): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4861): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4861): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4861): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4861): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4861): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4861): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4861): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4861): Couldn't open ClientFlag.db for writing (will try read-only):,
E/SQLiteOpenHelper( 4861): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4861): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4861): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849),
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4861): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4861): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4861): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4861): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4861): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4861): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4861): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4861): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4861): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4861): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4861): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4861): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4861): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4861): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4861): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4861): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4861): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4861): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4861): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4861): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4861): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4861): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4861): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4861): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4861): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4861): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4861): Opened ClientFlag.db in read-only mode,
,E/SQLiteDatabase( 4861): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 4861): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
,E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4861): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4861): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4861): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4861): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4861): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4861): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4861): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4861): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4861): ,	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4861): threadid=11: thread exiting with uncaught exception (group=0x416c4e30)
,E/AndroidRuntime( 4861): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4861): Process: com.google.android.apps.docs, PID: 4861
E/AndroidRuntime( 4861): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4861): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4861): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4861): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4861): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4861): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4861): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4861): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
,E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,E/SQLiteDatabase( 4861): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4861): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4861): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4861): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4861): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4861): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4861): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4861): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4861): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4861): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4861): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4861): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4861): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4861): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4861): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4861): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4861): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4861): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4882 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007},
D/Process ( 4861): killProcess, pid=4861,
D/Process ( 4861): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteOpenHelper( 4861): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4861): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4861): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4861): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4861): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4861): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4861): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4861): 	,at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4861): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4861): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4861): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4861): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4861): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4861): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4861): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4861): 	,at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4861): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4861): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4861): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4861): 	,at dalvik.system.NativeStart.main(Native Method)
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4861
,I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4861) has died.
,W/ContextImpl( 4882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4895 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4882): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4882): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4882): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4882): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4882): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4882): threadid=10: thread exiting with uncaught exception (group=0x416c4e30)
,E/ActivityManager(  907): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4882): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4882): Process: com.android.keychain, PID: 4882
,E/AndroidRuntime( 4882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4882): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4882): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4882): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4882): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,W/PackageManager(  907): Unable to load service info ResolveInfo{4216bdc8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b87e10 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,D/AppTag  ( 4895): getInstance(Context context)
,D/AppTag  ( 4895): getInstance(Context context)
,D/Process ( 4882): killProcess, pid=4882
D/Process ( 4882): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/AppTag  ( 4895): onCreate()
,E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453032997716.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  907): Recipient 4882
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.android.keychain (pid 4882) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20269ms
,I/ActivityManager(  907): Resuming delayed broadcast
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
D/PMS     (  907): acquireWL(4234b628): PARTIAL_WAKE_LOCK  AsyncService 0x1 4190 10160 null
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4912 uid=10098 gids={50098, 3003, 5012}
D/PMS     (  907): releaseWL(4234b628): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Killing 4506:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4506
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4506
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/DeviceManagement( 4912): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4912 dbg=false s=true
,I/DeviceManagement( 4912): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4912): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4912): WorkflowService: Starting workflow service
I/DeviceManagement( 4912): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b29218] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4912): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4912): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4912): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4912): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4912): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4912): SessionStateController: Checking invariants...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4928 uid=10099 gids={50099, 3003, 5012}
,D/Documents( 4928): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4928): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4928): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4928): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4928): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4928): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4928): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4928): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4928): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4928): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4928): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4928): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4928): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4928): threadid=1: thread exiting with uncaught exception (group=0x416c4e30)
E/AndroidRuntime( 4928): FATAL EXCEPTION: main
E/AndroidRuntime( 4928): Process: com.android.documentsui, PID: 4928
E/AndroidRuntime( 4928): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4928): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4928): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4928): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4928): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4928): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4928): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4928): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4928): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4928): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4928): 	... 10 more
,I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4942 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  907): killProcessQuiet, pid=3916
,I/ActivityManager(  907): Killing 3916:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/ActivityManager(  907): App crashed! Process: com.android.documentsui
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox

```
