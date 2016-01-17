#### Test 5615109389cecbd_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4720 uid=10077 gids={50077}
D/PMS     (  905): acquireWL(424c8cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
V/AlarmManager(  905): sending alarm PendingIntent{425c5380: PendingIntentRecord{427a32f8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453023970973, Int=60000
D/PMS     (  905): releaseWL(424c8cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
--------- beginning of /dev/log/main
D/SMSBackup( 4720): SMSBackupAgentService started
D/SMSBackup( 4720): Checking restore status
D/SMSBackup( 4720): Restore complete
D/SMSBackup( 4720): cancelCheckAlarm
D/SMSBackup( 4720): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  905): killProcessQuiet, pid=4222
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4222:com.google.android.music:main/u0a154 (adj 15): empty #17
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Recipient 4222
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.music (pid 4222): Died!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 13
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 39
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
E/cutils-trace( 4718): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4718): ====startRecUseTime====
D/htc.customization.log.level( 4718):  is 
W/CustomizationLogLevel( 4718): Level value is invalid, use default level 2
D/CustomizationManager( 4718):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4718): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4718): Parsing tag category name = system
I/CustomizationCIDLoader( 4718): Parsing tag category name = application
I/CustomizationCIDLoader( 4718): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4718): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4718): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4718): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4718): Parsing tag category name = Settings
D/CustomizationManager( 4718):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4718):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4718): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4718): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4718): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4718): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4718
D/PMS     (  905): acquireHCC(42e26100): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(441c65e8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x62eceb00 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1122118296
D/PMS     (  905): acquireWL(43508000): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f9ea20
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4742 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1269): [trimMemory] 20
W/asset   ( 4742): Copying FileAsset 0x5c7149b0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4742): Binding Chromium to main looper Looper (main, tid 1) {41a9d438}
I/LibraryLoader( 4742): Expected native library version number "",actual native library version number ""
I/chromium( 4742): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4742): Initializing chromium process, renderers=0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43569c60:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  905): acquireWL(447f55f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(4257b1d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(4257b1d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4742): 1101745888: getState(). Returning 12
I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
W/chromium( 4742): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4742): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4742): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4742): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4742): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4742): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4742): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4742): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4742): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4742): CordovaWebView is running on device made by: HTC
,W/AwContents( 4742): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1269
,W/ResourceType( 4742): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4742): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ae6590, mServedView=org.apache.cordova.engine.SystemWebView{41aac1f8 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  905): Enable input method client, pid=4742
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4742): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +276ms
,D/PMS     (  905): releaseWL(43508000): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/PMS     (  905): acquireWL(44179228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41ca21c8: PendingIntentRecord{4243ee88 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=101401, Int=0
,D/PMS     (  905): acquireWL(424582c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(44179228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43152ad8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(424582c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(43152ad8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/JsMessageQueue( 4742): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4742): JniHelper::setJavaVM(0x41575048), pthread_self() = 1663137296
,D/JX-Cordova( 4742): jxcore cordova android initializing
,I/dalvikvm-heap( 4742): Grow heap (frag case) to 11.994MB for 42652-byte allocation
,I/dalvikvm-heap( 4742): Grow heap (frag case) to 12.071MB for 95956-byte allocation
,I/dalvikvm-heap( 4742): Grow heap (frag case) to 12.151MB for 143930-byte allocation
,I/dalvikvm-heap( 4742): Grow heap (frag case) to 12.265MB for 215890-byte allocation
,I/dalvikvm-heap( 4742): Grow heap (frag case) to 12.441MB for 323830-byte allocation
,I/dalvikvm-heap( 4742): Grow heap (frag case) to 12.712MB for 485740-byte allocation
,I/dalvikvm-heap( 4742): Grow heap (frag case) to 13.681MB for 1092904-byte allocation
,I/dalvikvm-heap( 4742): Grow heap (frag case) to 14.632MB for 1639352-byte allocation
,I/dalvikvm-heap( 4742): Grow heap (frag case) to 15.877MB for 2459024-byte allocation
,I/dalvikvm-heap( 4742): Grow heap (frag case) to 18.066MB for 3688532-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(42e26100): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(441c65e8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4742): Initializing JXcore engine
,W/jxcore-log( 4742): JXcore engine is ready
,W/jxcore-log( 4742): Starting JXcore engine
,W/jxcore-log( 4742): Platform android
W/jxcore-log( 4742): 
,W/jxcore-log( 4742): Process ARCH arm
W/jxcore-log( 4742): 
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 13
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 52
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/jxcore-log( 4742): JXcore Cordova bridge is ready!
I/jxcore-log( 4742): 
,W/jxcore-log( 4742): JXcore engine is started
,I/Choreographer( 4742): Skipped 148 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4742): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  905): releaseWL(447f55f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4742): Toggling radios to true
I/jxcore-log( 4742): 
,D/BluetoothAdapter( 4742): enable(): BT is already enabled..!
,D/WifiManager( 4742): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1419
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
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
W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
,D/WifiManager( 4742): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4742): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): TDLS: Tear down peers
,I/wpa_supplicant( 1157): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4742): Radios toggled,
I/jxcore-log( 4742): 
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4742, uid=10189,
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
,I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
I/jxcore-log( 4742): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4742): 
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1157): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1157): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
,D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1157): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7d07bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1157):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1157): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1157): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/,wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
,D/wpa_supplicant( 1157): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  905):    returned true
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiPerfLock(  905): release()
,D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(42ec41b8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/wpa_supplicant( 1157): Fast associate: Old scan results
I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  905):    returned true
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19478 mDataStallAlarmIntent=PendingIntent{425095c8: PendingIntentRecord{4251bf68 android broadcastIntent}}
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
,D/WISPrService( 4129): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): Provision feature enable=false
D/WifiP2pService(  905): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1832/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4129): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  905): New client listening to asynchronous messages
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4129): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4129): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] entry_id:9   entry:0xb8103e20  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb8103d90  removed 
D/libc    (  365): [NET] entry_id:11   entry:0xb8103ea8  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8104340  removed 
D/libc    (  365): [NET] entry_id:10   entry:0xb8104ce0  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb81046f0  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8103fd8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8104248  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb8104818  removed 
D/libc    (  365): [NET] entry_id:12   entry:0xb8104da8  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb81040e8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8104410  removed 
D/libc    (  365): [NET] entry_id:13   entry:0xb8104e60  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1832/10178)
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/PMS     (  905): acquireWL(42e2c410): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1433 10028 null
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(43d39ac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1433 10028 null
D/PMS     (  905): acquireWL(42578c88): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): releaseWL(43d39ac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1433/10028)
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  905): releaseWL(42e2c410): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/PMS     (  905): releaseWL(42578c88): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4795 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  905): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  905): NoActiveNetworkState
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1510/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1870/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4535/10100)
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED,
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1832/10178)
D/PMS     (  905): acquireWL(42585d60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(42585d60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4535/10100)
,I/MusicStore( 4795): Database version: 95
,W/ContextImpl( 4795): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4795): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4795): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4795): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4795): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4795, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 4795): Registered
,I/MediaRouter( 4795): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4795/10154)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2874/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4815 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4795): getSelectedRoute
,I/NetworkMonitor( 4795): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4795/10154)
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4795, uid=10154, userID:0
,D/Process (  905): killProcessQuiet, pid=4548
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4548:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4548
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
D/ACRA    ( 4815): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4815): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4815): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4815): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4815): Preparing secondary program dexes.
V/DexLibLoader( 4815): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4815): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4815): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4815): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4815): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4815): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4815): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4815): Dex already copied
D/OdexVerifier( 4815): Odex verification is skipped.
,V/DexLibLoader( 4815): Creating class loader
,V/DexLibLoader( 4815): Finished creating class loader
V/DexLibLoader( 4815): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4815): Dex already copied
D/OdexVerifier( 4815): Odex verification is skipped.
,V/DexLibLoader( 4815): Creating class loader,
V/DexLibLoader( 4815): Finished creating class loader
V/DexLibLoader( 4815): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar,
V/DexLibLoader( 4815): Dex already copied
D/OdexVerifier( 4815): Odex verification is skipped.
,V/DexLibLoader( 4815): Creating class loader
,V/DexLibLoader( 4815): Finished creating class loader
V/DexLibLoader( 4815): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4815): Dex already copied
D/OdexVerifier( 4815): Odex verification is skipped.
,V/DexLibLoader( 4815): Creating class loader
,V/DexLibLoader( 4815): Finished creating class loader
,V/DexLibLoader( 4815): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4815): DexLibLoader.ensureDexLoaded took 16 ms
,W/dalvikvm( 4815): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4815): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4815): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4815): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4815): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4815): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4815): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1157): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1157): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1157): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1157): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 3
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 1
I/wpa_supplicant( 1157): wpa_s->is_screen_on 1
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): selected network = 1
D/wpa_supplicant( 1157): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7d094e8  current_ssid=0x0
D/wpa_supplicant( 1157): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1157): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1157): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1157): check if in concurrent case
,I/wpa_supplicant( 1157): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 1157): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1157): RSN: PMKSA cache search - network_ctx=0xb7d094e8 try_opportunistic=0
D/wpa_supplicant( 1157): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1157): State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1157): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1157): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 6,
D/wpa_supplicant( 1157): nl80211: Unsubscribe mgmt frames handle 0xb7d08718 (mode change)
D/wpa_supplicant( 1157): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7d08718
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7d08718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7d08718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7d08718,
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7d08718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7d08718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7d08718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7d08718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7d08718
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7d08718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7d08718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1157):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157):   * freq=2412
D/wpa_supplicant( 1157):   * Auth Type 0
D/wpa_supplicant( 1157):   * WPA Versions 0x2
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1157): nl80211: Connect request send successfully
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1157): reply (489) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-47
I/wpa_supplicant( 1157): tsf=0000000106402337
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-57
,I/wpa_supplicant( 1157): tsf=0000000106402354
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-57
I/wpa_supplicant( 1157): tsf=0000000106402348
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1157): ssid=01ABC
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=3
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2427
I/wpa_supplicant( 1157): level=-77
I/wpa_supplicant( 1157): tsf=0000000106402361
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ####
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING,
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 106402337, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 106402354, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 106402348, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 106402361, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1157): nl80211: Connect event
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1157): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1157): Add randomness: count=9 entropy=4
I/wpa_supplicant( 1157): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1157): TDLS: Remove peers on association
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1157): EAPOL: enable timer tick
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1157): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1157): Get randomness: len=32 entropy=5
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7d089f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1157):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  905): updateConnectedAP...
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1157): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f4bb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1157):    broadcast key
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1157): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1157): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1157): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1157): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=6
,I/wpa_supplicant( 1157): set send_ind_to_ndc = 0
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1157): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1157): EAPOL authentication completed successfully
I/wpa_supplicant( 1157): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WISPrService( 4129): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WISPrService( 4129): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 1
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(42081478): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
,D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423d48e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423d48e8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
,W/dalvikvm( 4815): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@41fe6920
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
,W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@41fe6920, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f79848
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@42584bf8
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #0: color=#0
,W/PMS     (  905): mWirelessDisplayManager is null
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/dalvikvm( 4815): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4815): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4815): Verify
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 368ms
I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1254): applyRouting - 0
,D/NfcService( 1254): ScreenObserver: OFF
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425c5500)
I/InputMethodManagerService(  905): Disable input method client, pid=4742
D/PMN     (  905): wakingUp
,D/NfcService( 1254): applyRouting -2
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/WifiService(  905): New client listening to asynchronous messages
D/PMS     (  905): acquireWL(441d9238): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/WindowManager(  905): No lock screen! windowToken=null
,D/PMS     (  905): acquireWL(429fa108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(441d9238): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/MtpService( 2874): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/NfcService( 1254): applyRouting - 0
,D/MtpService( 2874): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting -2
D/PMS     (  905): releaseWL(429fa108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  905): onScreenOn
D/PMS     (  905): acquireWL(4418c720): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  905): releaseWL(4418c720): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ClockThread( 1113): stop update clock
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): SET_SCREEN_ON:On
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0,
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1157): Change stage from stage0 to stage3
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
V/SRS_Proc(  372): ParamSet string: screen_state=on
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  905): updateScreenOn: false
,W/fb4a(:<default>):BaseAnalyticsConfig( 4815): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4815): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/dalvikvm-heap( 4815): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1800): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1800): onScreenOn: 1453023977659
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1800): onScreenOn: 1453023977659
,D/Process (  905): killProcessQuiet, pid=4204
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  905): acquireWL(425a1750): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1510 10028 null
D/PMS     (  905): releaseWL(425a1750): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  905): Killing 4204:com.htc.mediamanager/u0a32 (adj 15): empty #17
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f79848
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f79848, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@42584bf8
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(43286b80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2201 10028 null
D/PMS     (  905): acquireWL(43e5b750): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2201 10028 null
D/PMS     (  905): releaseWL(43286b80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/PMS     (  905): acquireWL(425bcf00): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19479 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/PMS     (  905): acquireWL(43d6e5c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): SET_SCREEN_ON:Off
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1157): get_ip_address source addr = 02000000
I/wpa_supplicant( 1157): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
D/PMS     (  905): releaseWL(43d6e5c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2201/10028)
,D/GCM     ( 1433): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2201/10028)
D/PMS     (  905): releaseWL(43e5b750): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/NetworkPolicy(  905): updateScreenOn: false
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/AutoSetting( 1397): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4855 uid=10078 gids={50078, 3003, 5012}
,I/ActivityManager(  905): Recipient 4204
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1397/10053)
,D/AutoSetting( 1397): Util - no network available!
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1397/10053)
,D/AutoSetting( 1397): service - onCreate()
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,W/fb4a(:<default>):UserScope( 4815): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4815): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutoSetting( 1397): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  905): request 41d950e8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1397): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1397): service - mHandler: cancel location update
,D/AutoSetting( 1397): service -           changes count: 0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1800): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1800): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1800): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1800): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1800): onScreenOff
D/PMS     (  905): acquireWL(4335f018): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1510 10028 null
,D/PMS     (  905): releaseWL(4335f018): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/fb4a(:<default>):UserScope( 4815): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4855): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4855): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4855): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4855): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4872 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4855/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4855/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4855/10078)
,E/dalvikvm( 4815): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4815): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4815): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4815): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4815): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4815): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4815): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4815): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4815): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4815): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4815): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4815): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4815): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4815): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4815): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4815): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4815): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4815): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4886 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4597
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4597:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4597
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4815): Grow heap (frag case) to 9.905MB for 39954-byte allocation
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4886): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4886): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 4742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4742): 
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1157): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1157): EAPOL: disable timer tick
,I/dalvikvm-heap( 4815): Grow heap (frag case) to 9.981MB for 79892-byte allocation
,W/GAV2    ( 4886): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4886): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4886): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4815): Grow heap (frag case) to 10.043MB for 84664-byte allocation
,I/dalvikvm-heap( 4815): Grow heap (frag case) to 10.257MB for 75760-byte allocation
,V/WebViewChromiumFactoryProvider( 4886): Binding Chromium to main looper Looper (main, tid 1) {41aa4270}
,I/LibraryLoader( 4886): Expected native library version number "",actual native library version number ""
,I/chromium( 4886): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4886/10151)
I/BrowserStartupController( 4886): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(424de288): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/PMS     (  905): acquireWL(435f9128): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  905): releaseWL(424de288): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43dff048 u0 ReceiverList{43dfef28 4815 com.facebook.katana/10026/u0 remote:43dc0440}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43dff048 u0 ReceiverList{43dfef28 4815 com.facebook.katana/10026/u0 remote:43dc0440}}
,E/AudioManagerAndroid( 4886): BLUETOOTH permission is missing!
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42a92508 u0 ReceiverList{427bc198 4815 com.facebook.katana/10026/u0 remote:4260eb48}}
,I/Adreno-EGL( 4886): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4886): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4886): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4886): Local Branch: 
I/Adreno-EGL( 4886): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4886): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4886):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,I/NSApplication( 4886): Starting up...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4886/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4886/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3905/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3905/10160)
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{41bde678 u0 com.test.thalitest/.MainActivity t2}
,D/Process (  905): killProcessQuiet, pid=4535
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/GCoreFlp( 1510): Unknown pending intent to remove.
I/ActivityManager(  905): Killing 4535:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/PMS     (  905): acquireWL(42eb26c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1510 10028 null
D/PMS     (  905): releaseWL(42eb26c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1832/10178)
,D/AutoSetting( 1397): receiver - intent: android.intent.action.USER_PRESENT
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1832/10178)
I/ActivityManager(  905): Recipient 4535
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TetherSettings( 4129): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4129): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4129): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4129): Cust_ConnectToPC   : spcsc>false
D/        ( 4129): Cust_ConnectToPC   : IPT>true
D/        ( 4129): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4129): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4129): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4129): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4129): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1397): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 4129): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 4129): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 4129): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4129): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4129):  defaultType:0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4815): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4927 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4815): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4815): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4927): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4927): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(435d3c28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4927 1000 null
,D/PMS     (  905): releaseWL(435d3c28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4927): getMobilePolicyEnabled, result = true
,D/Process (  905): killProcessQuiet, pid=4636
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4636:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4636
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SmartSyncUtils( 4927): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4927): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4927): isEpsOn(), nState = 0
W/ContextImpl( 4927): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42584bf8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  905): New client listening to asynchronous messages
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42584bf8, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
D/GCM     ( 1433): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42584bf8, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42584bf8
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424f6f88 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424f6f88 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/jxcore-log( 4742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4742): 
,I/jxcore-log( 4742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4742): 
,I/jxcore-log( 4742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4742): 
,I/jxcore-log( 4742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4742): 
,I/jxcore-log( 4742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4742): 
,I/jxcore-log( 4742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4742): 
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(42081478): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1157): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  905): WAN detection
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4129): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=100 [1][1][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@423cc5f0
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1832/10178)
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(436a2f90): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4855/10078)
,D/PMS     (  905): acquireWL(442e35e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2201 10028 null
I/QuickSettingWifi( 1113): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(436a2f90): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  905): acquireWL(43d1fb08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2201 10028 null
D/PMS     (  905): releaseWL(442e35e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
I/CheckinService( 2201): Preparing to send checkin request
,I/EventLogService( 2201): Accumulating logs since 1453023919932
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2201/10028)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
I/GoogleHttpClient( 2201): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2201): Using GMS GoogleHttpClient
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2201/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2201/10028)
,W/GLSUser ( 1433): GoogleAccountDataService.getToken()
,W/GLSActivity( 1433): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1433): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1433): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 2201): awaiting user notification for token
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41ae7ce8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 1 10 2 12
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4980 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4980): install
,I/MultiDex( 4980): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4980): loading existing secondary dex files
,I/MultiDex( 4980): load found 1 secondary dex files
,I/MultiDex( 4980): install done
,I/ProviderInstaller( 4980): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1433): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/jxcore-log( 4742): Test app app.js loaded
I/jxcore-log( 4742): 
,I/Choreographer( 4742): Skipped 274 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4742): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4742): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aac1f8 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  905): releaseWL(425bcf00): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4742): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4980/10028)
,I/Adreno-EGL( 4980): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4980): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4980): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4980): Local Branch: 
I/Adreno-EGL( 4980): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4980): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4980):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4980): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4980): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4980): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4980): Local Branch: 
I/Adreno-EGL( 4980): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4980): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4980):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4980): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4980): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4980): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4980): Local Branch: 
I/Adreno-EGL( 4980): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4980): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4980):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4980): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  905): releaseWL(42ec41b8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
V/Tethering(  905): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/CaptivePortalTracker(  905): NoActiveNetworkState
,I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  905): acquireWL(44105740): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(44105740): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1832/10178)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4795/10154)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [3][0][0]
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/NetworkMonitor( 4795): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1157): Change stage from stage3 to stage0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4855/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1510/10028)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1870): Checking Certificates
I/acms    ( 1870): Checking Developer Certificates
I/acms    ( 1870): Checking Application Certificates
I/acms    ( 1870): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1870): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1870): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1870): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1870): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1870): Updating next query delay: 75600000
I/mlserverapp( 1870): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1870): cancelACMSProgrammedChecks
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1870/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (4244/10051)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1510/10028)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(434e5b08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2874/10021)
E/ExternalAccountType( 1328): Unsupported attribute readOnly
D/PMS     (  905): acquireWL(42596320): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
D/PMS     (  905): releaseWL(434e5b08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(424ab450): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(424ab450): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4523): Last usage 0, idle 1453023979s, sync interval 2592000s
,I/NewsWeather( 4523): setPeriodicSync in seconds 2592000
D/PMS     (  905): acquireWL(4418ad40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2201 10028 null
D/PMS     (  905): releaseWL(4418ad40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1433): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
I/NewsWeather( 4523): Skip sync for lookup editions
,I/NewsWeather( 4523): syncNewsAppData traffic type BACKGROUND_POLL
D/libc    ( 1433): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1433): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
,D/PMS     (  905): acquireWL(4354a338): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1433 10028 null
D/libc    ( 1433): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1433): [NET] getaddrinfo-, 1
D/libc    ( 1433): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =73e8 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2201/10028)
,I/NewsWeather( 4523): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/AutoSetting( 1397): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1397/10053)
D/MobileConnectivityChangeReceiver( 4855): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4855): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1397): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1397): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1397): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1397): service - onStartCommand() check timezone in 30000
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 281
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1397/10053)
,D/libc    ( 1433): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4886/10151)
,W/GLSUser ( 1433): GoogleAccountDataService.getToken()
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3905/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3905/10160)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
W/GLSActivity( 1433): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1433): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1433): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1832/10178)
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,E/NewsWeather( 4523): Unrecoverable authentication exception
E/NewsWeather( 4523): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4523): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4523): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4523): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41e4a258 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,V/NativeCrypto( 4523): Read error: ssl=0x637bacc8: I/O error during system call, Connection timed out
,I/RemoteViews.Performance( 1113): com.google.android.gms 1 8 3 12
,V/NativeCrypto( 4523): SSL shutdown failed: ssl=0x637bacc8: I/O error during system call, Broken pipe
,D/libc    ( 4523): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4523): [NET] getaddrinfo-,err=8
D/libc    ( 4523): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    ( 4523): [NET] getaddrinfo-, 1
,D/libc    ( 4523): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a8e2 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/libc    ( 1433): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1433): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/PMS     (  905): acquireWL(42e085a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1433 10028 null
D/AutoSetting( 1497): service - onDestroy() END
,D/AutoSetting( 1497): service - handleMessage() quit looper
D/PMS     (  905): releaseWL(42e085a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=70
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4523): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4523): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4523): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2201): Sending checkin request (9003 bytes)
,D/libc    ( 2201): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2201): [NET] getaddrinfo-,err=8
,D/libc    ( 2201): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2201): [NET] getaddrinfo-, 1
,D/libc    ( 2201): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ec46 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/PMS     (  905): acquireWL(42dfb580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1433 10028 null
,D/GCM     ( 1433): Connected
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2201): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/PMS     (  905): releaseWL(4354a338): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1433/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/PMS     (  905): releaseWL(42dfb580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(42de1ba8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1433 10028 null
,E/NewsWeather( 4523): Failed to syncNewsAppData
,E/NewsWeather( 4523): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): acquireWL(42dd9e90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1433 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4267a768): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/libc    ( 2201): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2201): [NET] getaddrinfo-,err=8
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 72343, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/Process (  905): killProcessQuiet, pid=4656
D/PMS     (  905): releaseWL(42dd9e90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  905): releaseWL(42596320): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,I/ActivityManager(  905): Killing 4656:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
D/PMS     (  905): releaseWL(4267a768): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1510/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(44187fd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1433/10028)
D/PMS     (  905): releaseWL(44187fd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1433): Message class mpf
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
I/ActivityManager(  905): Recipient 4656
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1433/10028)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
,D/PMS     (  905): releaseWL(42de1ba8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  905): acquireWL(435a4290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1433 10028 null
D/PMS     (  905): releaseWL(435a4290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,W/fb4a(:<default>):UserScope( 4815): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4815): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=6 [29][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4815): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/libc    ( 4815): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4815): [NET] getaddrinfo-,err=8
D/libc    ( 4815): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4815): [NET] getaddrinfo-, 1
,D/libc    ( 4815): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ee3e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/PMS     (  905): acquireWL(43d9ac28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1433 10028 null
,D/PMS     (  905): releaseWL(43d9ac28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 39
D/libc    (  365): [NET]res_nsend:resplen=74
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4815): [NET] getaddrinfo_proxy-, success
I/global  ( 4815): call createSocket() return a new socket.
D/libc    ( 4815): [NET] getaddrinfo+,hn 12(0x3137392e36302e),sn(),family 0,flags 4
,D/libc    ( 4815): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2201/10028)
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2201/10028)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=25 [4][1][0]
,W/GLSUser ( 1433): GoogleAccountDataService.getToken()
D/PMS     (  905): acquireWL(42329978): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4795 10154 null
,W/ContextImpl( 4795): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/GLSActivity( 1433): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1433): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1433): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ContextImpl( 4795): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2201): awaiting user notification for token
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41e75248 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 2 10 3 12
,I/CheckinTask( 2201): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2201): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2201/10028)
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4795, uid=10154, userID:0
,D/PMS     (  905): releaseWL(42329978): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 4795): Conditions not met for autocaching.
,I/MusicLeanback( 4795): Stop autocaching.
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2201/10028)
,D/PMS     (  905): releaseWL(43d1fb08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1433): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 2201): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d560e0 that was originally bound here
E/ActivityThread( 2201): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d560e0 that was originally bound here
E/ActivityThread( 2201): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2201): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2201): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2201): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2201): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2201): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2201): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2201): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2201): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2201): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2201): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2201): 	at bks.a(SourceFile:298)
E/ActivityThread( 2201): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2201): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2201): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2201): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1433): GCM config loaded
,D/libc    ( 4815): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4815): [NET] getaddrinfo-,err=8
,D/PMS     (  905): releaseWL(435f9128): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/dalvikvm-heap( 4815): Grow heap (frag case) to 10.968MB for 32784-byte allocation
,I/dalvikvm-heap( 4815): Grow heap (frag case) to 10.994MB for 32784-byte allocation
,D/PMS     (  905): acquireWL(4255d128): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4815 10026 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4815/10026)
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6c67 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,I/global  ( 4815): I/O error closing connection
I/global  ( 4815): java.net.SocketException: Socket is closed
I/global  ( 4815): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4815): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4815): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4815): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4815): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4815): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4815): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4815): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4815): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4815): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4815): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4815): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4815): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4815): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4815): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4815): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4815): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4815): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4815): Removing a connection that never existed!
D/PMS     (  905): releaseWL(4255d128): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/GAV2    ( 4886): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=4622
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4622:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4622
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=4244
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4244:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4244
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1397): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1397): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1397): service - requestNLP() NetworkLocationProvider not enabled
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42ddd4f0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(42de7d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(42de7d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(436d9db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(436d9db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43e181a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41ca21c8: PendingIntentRecord{4243ee88 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=135552, Int=0
,D/PMS     (  905): acquireWL(43e51e48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): releaseWL(43e181a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(424ccf10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43e51e48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(424ccf10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1397): service - mHandler: update timezone
,D/AutoSetting( 1397): service - handleMessage() stop self
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1497): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1397): service - handleMessage() quit looper
D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1397): service - onDestroy() END
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  905): batLight: Full, plugged
,D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1497): service - mHandler: update timezone
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1497): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1497): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41e893e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 2 8 2 11
,D/PMS     (  905): acquireWL(434d0020): PARTIAL_WAKE_LOCK  Icing 0x1 2201 10028 null
,D/PMS     (  905): releaseWL(434d0020): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(42b88488): PARTIAL_WAKE_LOCK  Icing 0x1 2201 10028 null
,D/PMS     (  905): releaseWL(42b88488): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(43d67ab8): PARTIAL_WAKE_LOCK  Icing 0x1 2201 10028 null
,D/PMS     (  905): releaseWL(43d67ab8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(42eba770): PARTIAL_WAKE_LOCK  Icing 0x1 2201 10028 null
,D/PMS     (  905): releaseWL(42eba770): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(442d25a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10028}
,V/AlarmManager(  905): sending alarm PendingIntent{43d1ca10: PendingIntentRecord{42338ba0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137351, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1433/10028)
,V/AlarmManager(  905): sending alarm PendingIntent{41fe4ad0: PendingIntentRecord{424ae820 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141086, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(43593810): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): acquireWL(435a2e80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1433 10028 null
D/PMS     (  905): releaseWL(442d25a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): releaseWL(435a2e80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a0ad +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 53
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(43593810): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  905): acquireWL(42e8dd48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422aef38: PendingIntentRecord{422ae7b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149564, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42e8dd48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{435e4480 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  905): acquireWL(439e2ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41ca21c8: PendingIntentRecord{4243ee88 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=165568, Int=0
,D/PMS     (  905): acquireWL(440f5250): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(439e2ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43232158): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=12 [73][9][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(44121bf8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,D/PMS     (  905): releaseWL(440f5250): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43232158): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(437b7be0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(437b7be0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4523): Last usage 0, idle 1453024036s, sync interval 2592000s
I/NewsWeather( 4523): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4523): Skip sync for lookup editions
,I/NewsWeather( 4523): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4523): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1433): GoogleAccountDataService.getToken()
,W/GLSActivity( 1433): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1433): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1433): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,E/NewsWeather( 4523): Unrecoverable authentication exception
E/NewsWeather( 4523): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4523): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4523): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4523): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41ae7a40 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 1 8 3 12
,D/PMS     (  905): acquireWL(43630778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1433 10028 null
,E/NewsWeather( 4523): Failed to syncNewsAppData
,E/NewsWeather( 4523): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): releaseWL(43630778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(434fa338): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 109815, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(44121bf8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  905): releaseWL(434fa338): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1510/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(441965a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(441965a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=4158
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1497): service - handleMessage() quit looper
I/ActivityManager(  905): Killing 4158:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PMS     (  905): acquireWL(440f3c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{425b71b8: PendingIntentRecord{42662028 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=169858, Int=0
,D/PMS     (  905): releaseWL(440f3c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,I/ActivityManager(  905): Recipient 4158
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(44190170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44190170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(424d3100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41ca21c8: PendingIntentRecord{4243ee88 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=195619, Int=0
,D/PMS     (  905): acquireWL(431d0938): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(424d3100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(420bd510): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(431d0938): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(420bd510): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(4242bf00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422aef38: PendingIntentRecord{422ae7b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209564, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4242bf00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42929838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41ca21c8: PendingIntentRecord{4243ee88 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=229178, Int=0
,D/PMS     (  905): acquireWL(4267bd90): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42929838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43b8dc98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=13 [23][3][0]
I/wpa_supplicant( 1157): Change stage from stage0 to stage3
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(437c9168): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
D/PMS     (  905): releaseWL(4267bd90): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  905): releaseWL(43b8dc98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4413cb10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4413cb10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4523): Last usage 0, idle 1453024099s, sync interval 2592000s
,I/NewsWeather( 4523): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4523): Skip sync for lookup editions
,I/NewsWeather( 4523): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4523): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1433): GoogleAccountDataService.getToken()
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2201/10028)
,W/GLSActivity( 1433): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1433): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1433): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,E/NewsWeather( 4523): Unrecoverable authentication exception
E/NewsWeather( 4523): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4523): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4523): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4523): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4523): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41e4a258 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 3 12 4 12
,W/GA-SERVICE( 2201): Thread[Thread-189,5,main]: hit:_gmsv=1-5089038&ul=en-gb&sr=720x1184&ht=1453023904357&a=1336221837&sc=start&AppUID=10151&aid=com.google.android.apps.magazines&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&cd16=Ignoring+sync+request+for+non-current+account&v=1&t=appview&an=Google+Play+Newsstand&cd11=false&tid=UA-32428711-6&_u=.nOQKSTB&_v=ma1b6&cd=Debug&qt=195593&z=131
,W/GA-SERVICE( 2201): Thread[Thread-189,5,main]: hit:_gmsv=1-5089038&ev=0&ul=en-gb&sr=720x1184&ht=1453023904358&a=1230163294&AppUID=10151&aid=com.google.android.apps.magazines&ea=Sync+Skipped&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&ec=Debug&v=1&t=event&el=&an=Google+Play+Newsstand&tid=UA-32428711-6&_u=.C&_v=ma1b6&cd=Debug&qt=195592&z=132
D/libc    ( 2201): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 4
D/libc    ( 2201): [NET] getaddrinfo-,err=8
D/libc    ( 2201): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    ( 2201): [NET] getaddrinfo-, 1
,D/libc    ( 2201): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ae88 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,E/NewsWeather( 4523): Failed to syncNewsAppData
,E/NewsWeather( 4523): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): acquireWL(427a5128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1433 10028 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 166054, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43633ee0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(427a5128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  905): releaseWL(437c9168): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=102
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2201): [NET] getaddrinfo_proxy-, success
I/global  ( 2201): call createSocket() return a new socket.
D/libc    ( 2201): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2201): [NET] getaddrinfo-, SUCCESS
D/PMS     (  905): releaseWL(43633ee0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1510/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(427731a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  905): releaseWL(427731a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43c671f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c671f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(426eeee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41ca21c8: PendingIntentRecord{4243ee88 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=259229, Int=0
,D/PMS     (  905): acquireWL(42550fe0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(426eeee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43e5fbd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42550fe0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(43e5fbd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(43e17090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422aef38: PendingIntentRecord{422ae7b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=269565, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43e17090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4262ed28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4262ed28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4742): --= Surplus to requirements =--
I/jxcore-log( 4742): 
I/jxcore-log( 4742): ****TEST TOOK:  ms ****
I/jxcore-log( 4742): 
,I/jxcore-log( 4742): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4742): 
,E/cutils-trace( 5055): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 5055): ====startRecUseTime====
D/htc.customization.log.level( 5055):  is 
,W/CustomizationLogLevel( 5055): Level value is invalid, use default level 2
,D/CustomizationManager( 5055):  Read ACC file spent 0.112 (s)
D/CIDMapFileReader( 5055): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5055): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5055): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5055): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5055): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5055): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5055): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5055): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5055): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5055): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5055): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 5055): Parsing tag category name = system
I/CustomizationCIDLoader( 5055): Parsing tag category name = application,
I/CustomizationCIDLoader( 5055): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5055): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 5055): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5055): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5055): Parsing tag category name = Settings,
D/CustomizationManager( 5055):  Read CID file spent 0.169 (s)
,D/CustomizationManager( 5055):  All configurations done spent 0.169 (s)
,W/HtcNativeFlag( 5055): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5055): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5055): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 5055): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=5055, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4742
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905): Killing 4742:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
I/ActivityManager(  905):   Force finishing activity ActivityRecord{41bde678 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  905): Copying FileAsset 0x5cb34b10 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,W/InputDispatcher(  905): channel '424c8e58 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '424c8e58 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '424c8e58 com.test.thalitest.MainActivity (s)'
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4742 uid 10189
I/WindowState(  905): WIN DEATH: Window{424c8e58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/WindowManager(  905): WINDOW DIED Window{424c8e58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
,W/GeofencerStateMachine( 1510): Ignoring removeGeofence because network location is disabled.
,I/acms    ( 1870): Unregistering com.test.thalitest
I/Launcher( 1269): Deferring update until onResume
D/Launcher( 1269): waitUntilResume // bindAppsRemoved
,E/acms    ( 1870): Could not unregister removed application com.test.thalitest
D/PMS     (  905): acquireWL(442095b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1510 10028 null
D/PMS     (  905): releaseWL(442095b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/VoicemailCleanupService( 1295): Cleaning up data for package: com.test.thalitest
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto",
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PackageBroadcastService( 2201): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=5072 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  905):   Scheme: "sms"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
,I/MultiDex( 5072): install
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
,I/MultiDex( 5072): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/MultiDex( 5072): loading existing secondary dex files
,I/MultiDex( 5072): load found 1 secondary dex files
,I/MultiDex( 5072): install done
I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5090 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/PeopleContactsSync( 2201): CP2 sync disabled
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2201, uid=10028, userID:0
,I/ProviderInstaller( 5072): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/Icing   ( 2201): doRemovePackageData com.test.thalitest
,E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 2201): Could not init tag ds.tag.corpusid-1
,E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 2201): Could not init tag ds.tag.corpusid-12
,D/PMS     (  905): acquireWL(43a392b0): PARTIAL_WAKE_LOCK  Icing 0x1 2201 10028 null
E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 2201): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 2201): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 2201): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 2201): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 2201): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 2201): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 2201): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 2201): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 2201): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,E/Icing   ( 2201): Writing status failed
D/PMS     (  905): releaseWL(43a392b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 5090): install
,I/MultiDex( 5090): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 5090): loading existing secondary dex files
,I/MultiDex( 5090): load found 1 secondary dex files
,I/MultiDex( 5090): install done
,E/SQLiteDatabase( 2201): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2201): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2201): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2201): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2201): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2201): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2201): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2201): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2201): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2201): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2201): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2201): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2201): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ProviderInstaller( 5090): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,E/ClearPendingStateOp( 2201): Runtime exception while performing operation
E/ClearPendingStateOp( 2201): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2201): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2201): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2201): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2201): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2201): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2201): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2201): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2201): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2201): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2201): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,F/ClearPendingStateOp( 2201): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2201): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2201): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2201): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2201): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2201): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2201): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2201): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2201): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2201): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2201): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2201): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2201): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4677
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 4677:com.htc.calendar/u0a13 (adj 15): empty #17
E/SharedPreferencesImpl( 1207): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
,E/DropBoxManagerService(  905): Can't write: system_app_wtf
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
,I/[PluginManager]RegisterService( 1397): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1397): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
,E/SQLiteDBG( 1397): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9aeaa0
I/ActivityManager(  905): Recipient 4677
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/[PluginManager]RegisterService( 1397): provider may killed!
W/[PluginManager]RegisterService( 1397): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1397): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1397): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1397): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1397): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1397): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1397): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1397): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1397): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1397): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 3282): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5112 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 5072): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 5072): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5072): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5072): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5072): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 5072): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 5072): 	at ctn.run(SourceFile:985)
,W/dalvikvm( 5072): threadid=12: thread exiting with uncaught exception (group=0x4166de30)
,E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 5072): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5072): Process: com.google.android.gms.drive, PID: 5072
E/AndroidRuntime( 5072): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5072): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5072): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5072): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5072): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 5072): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 5072): 	at ctn.run(SourceFile:985)
,E/DropBoxManagerService(  905): Can't write: system_app_crash
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
,D/Process ( 5072): killProcess, pid=5072
,D/Process ( 5072): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/SQLiteLog( 3282): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3282): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64842a80
,W/dalvikvm( 3282): threadid=16: thread exiting with uncaught exception (group=0x4166de30)
,E/AndroidRuntime( 3282): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 3282): Process: com.google.android.googlequicksearchbox:search, PID: 3282
E/AndroidRuntime( 3282): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3282): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3282): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 3282): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3282): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3282): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 3282): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 3282): 	at cid.d(PG:186)
E/AndroidRuntime( 3282): 	at clo.g(PG:594)
E/AndroidRuntime( 3282): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 3282): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 3282): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 3282): 	at clp.Rl(PG:910)
E/AndroidRuntime( 3282): 	at clr.tL(PG:827)
E/AndroidRuntime( 3282): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 3282): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 3282): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3282): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3282): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3282): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
,D/Process ( 3282): killProcess, pid=3282
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 3282): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
,I/ActivityManager(  905): Recipient 5072
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.google.android.gms.drive (pid 5072) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,I/ActivityManager(  905): Recipient 3282
,I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 3282) has died.
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 3282): Died!
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/WifiService(  905): Client connection lost with reason: 4
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteDatabase( 5112): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.,
E/SQLiteDatabase( 5112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5112): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5112): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
,E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5112): ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5112): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5112): ,	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5112): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5112): 	at aGL.a(GellyInjectorStoreBase.java:136),
E/SQLiteDatabase( 5112): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5112): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5112): 	at fx.a(GellyInjectorStore.java:95)
,E/SQLiteDatabase( 5112): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5112): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5112): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5112): 	at Tk.a(ScopedInjector.java:216)
,E/SQLiteDatabase( 5112): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5112): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5112): 	at android.os.Looper.loop(Looper.java:157)
,E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5112): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5112): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5112): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5112): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5112): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5112): Couldn't open ClientFlag.db for writing (will try read-only):,
E/SQLiteOpenHelper( 5112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5112): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5112): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5112): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5112): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5112): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5112): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5112): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5112): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5112): 	,at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5112): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5112): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5112): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5112): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5112): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5112): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153),
E/SQLiteOpenHelper( 5112): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5112): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5112): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5112): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5112): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5112): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896),
E/SQLiteOpenHelper( 5112): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5112): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 5112): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 5112): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5112): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5112): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5112): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5112): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5112): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 5112): threadid=11: thread exiting with uncaught exception (group=0x4166de30)
,E/AndroidRuntime( 5112): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5112): Process: com.google.android.apps.docs, PID: 5112
E/AndroidRuntime( 5112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5112): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
,E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5112): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5112): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5112): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5112): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5112): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
,E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5131 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/SQLiteDatabase( 5112): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5112): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5112): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5112): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5112): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5112): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5112): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5112): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5112): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5112): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 5112): killProcess, pid=5112
D/Process ( 5112): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteOpenHelper( 5112): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5112): 	at android.database.sql,ite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5112): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5112): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5112): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5112): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5112): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5112): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5112): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5112): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5112): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5112): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5112): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5112): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5112): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  905): Recipient 5112
,I/ActivityManager(  905): Process com.google.android.apps.docs (pid 5112) has died.
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 5131): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b30f50 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5144 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 5131): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5131): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5131): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5131): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5131): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5131): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5131): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5131): threadid=10: thread exiting with uncaught exception (group=0x4166de30)
E/AndroidRuntime( 5131): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5131): Process: com.android.keychain, PID: 5131
E/AndroidRuntime( 5131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5131): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5131): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5131): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5131): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5131): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5131): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox

```
