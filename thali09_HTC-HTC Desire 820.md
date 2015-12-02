#### Test 5198634075bb434_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  913): Waited long enough for: ServiceRecord{43c873e0 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4391): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4391): ====startRecUseTime====
D/htc.customization.log.level( 4391):  is 
W/CustomizationLogLevel( 4391): Level value is invalid, use default level 2
D/CustomizationManager( 4391):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4391): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4391): Parsing tag category name = system
I/CustomizationCIDLoader( 4391): Parsing tag category name = application
I/CustomizationCIDLoader( 4391): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4391): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4391): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4391): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4391): Parsing tag category name = Settings
D/CustomizationManager( 4391):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4391):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 4391): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4391): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4391): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4391): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  913): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  913): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  913): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  913): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  913): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  913): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  913): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4391
D/PMS     (  913): acquireHCC(44259240): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 913 1000 null
D/PMS     (  913): acquireHCC(44218c28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 913 1000 null
W/asset   (  913): Copying FileAsset 0x62c82b68 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  913): @test_code: getHtcIntentFlag: 0 obj: 1142330584
D/PMS     (  913): acquireWL(441a6ab0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 913 1000 null
I/FeedHostManager( 1278): [onPause]
I/FeedProviderManager( 1278): onPause
I/SocialFeedProvider( 1278): +onPause
I/FeedHostManager( 1278): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4222c198
I/SocialFeedProvider( 1278): -onPause
I/ActivityManager(  913): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4402 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1278): [trimMemory] 20
W/asset   ( 4402): Copying FileAsset 0x5c7b5618 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4402): Binding Chromium to main looper Looper (main, tid 1) {41b35480}
I/LibraryLoader( 4402): Expected native library version number "",actual native library version number ""
I/chromium( 4402): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4402): Initializing chromium process, renderers=0
D/BluetoothManagerService(  913): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  913): java.lang.Throwable: stack dump
D/BluetoothManagerService(  913): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42475208:true
W/System.err(  913): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/PMS     (  913): acquireWL(43b19f68): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  913): acquireWL(439bdf90): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  913): releaseWL(439bdf90): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  913): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  913): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  913): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  913): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4402): 1102360248: getState(). Returning 12
I/Adreno-EGL( 4402): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4402): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4402): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4402): Local Branch: 
I/Adreno-EGL( 4402): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4402): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4402):                  aa63bbd948f41d15fc72f585e
W/chromium( 4402): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4402): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4402): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4402): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4402): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4402): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4402): CordovaWebView is running on device made by: HTC
,W/AwContents( 4402): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  913): Disable input method client, pid=1278
,W/ResourceType( 4402): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4402): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b7c568, mServedView=org.apache.cordova.engine.SystemWebView{41b421d0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1213): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1213): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  913): Enable input method client, pid=4402
,W/AwContents( 4402): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  913): Displayed com.test.thalitest/.MainActivity: +274ms
,D/PMS     (  913): releaseWL(441a6ab0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4402): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4402): JniHelper::setJavaVM(0x41605048), pthread_self() = 1663528032
,D/JX-Cordova( 4402): jxcore cordova android initializing
,W/dalvikvm( 4402): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.615MB for 146998-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.731MB for 220492-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.910MB for 330734-byte allocation
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 12.188MB for 496096-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 12.600MB for 744140-byte allocation
,V/LightsService(  913): setLight #0: color=#3f
,V/LightsService(  913): setLight #0: color=#3b
,V/LightsService(  913): setLight #0: color=#35
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 14.071MB for 1674304-byte allocation
V/LightsService(  913): setLight #0: color=#2e
,V/LightsService(  913): setLight #0: color=#27
,D/PMS     (  913): acquireWL(438e64c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10074}
,V/AlarmManager(  913): sending alarm PendingIntent{426633e0: PendingIntentRecord{424d7b78 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449063136862, Int=0
,I/ActivityManager(  913): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4446 uid=10078 gids={50078}
,V/AlarmManager(  913): sending alarm PendingIntent{425edbf8: PendingIntentRecord{4255c0d8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449063141762, Int=60000
,D/PMS     (  913): releaseWL(438e64c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,V/LightsService(  913): setLight #0: color=#21
,D/SMSBackup( 4446): SMSBackupAgentService started
,D/SMSBackup( 4446): Checking restore status
,V/LightsService(  913): setLight #0: color=#1a
D/SMSBackup( 4446): Restore complete
,D/SMSBackup( 4446): cancelCheckAlarm
,D/SMSBackup( 4446): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,V/LightsService(  913): setLight #0: color=#14
,I/SensorManager(  913): mEventCount = 901
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 15.506MB for 2511452-byte allocation
,D/Finsky  ( 4047): [419] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4047): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  913): killProcessQuiet, pid=2930
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 2930:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 2930
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 17.556MB for 3767174-byte allocation
,W/jxcore-log( 4402): Initializing JXcore engine
,W/jxcore-log( 4402): JXcore engine is ready
,W/jxcore-log( 4402): Starting JXcore engine
,W/CpuWake (  913): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  913): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  913): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  913): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  913): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  913): <<release mCpuPerf_Freq wakelock
D/PMS     (  913): releaseHCC(44259240): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  913): releaseHCC(44218c28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 4402): Platform android
W/jxcore-log( 4402): 
,W/jxcore-log( 4402): Process ARCH arm
W/jxcore-log( 4402): 
,I/jxcore-log( 4402): JXcore Cordova bridge is ready!
I/jxcore-log( 4402): 
,W/jxcore-log( 4402): JXcore engine is started
,I/chromium( 4402): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4402): Toggling radios to true
I/jxcore-log( 4402): 
,D/BluetoothAdapter( 4402): enable(): BT is already enabled..!
,D/WifiManager( 4402): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  913): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  913): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  913): Settings:Agentvalue: 2
W/Settings:Agent(  913): >> traceCallingStack()
W/Settings:Agent(  913): Process.myPid(): 913
,W/Settings:Agent(  913): Process.myTid(): 1276
W/Settings:Agent(  913): Process.myUid(): 1000
W/Settings:Agent(  913): 
,W/Settings:Agent(  913): 
D/WifiService(  913): setWifiEnabled: true pid=4402, uid=10389
D/WifiService(  913): New client listening to asynchronous messages
E/WifiService(  913): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  913): isSprintWifiRestricted(): false
I/WifiService(  913): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  913): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  913): java.lang.Throwable: stack dump
W/System.err(  913): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  913): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  913): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  913): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  913): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  913): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  913): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  913): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  913): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  913): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  913): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  913): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  913): 
W/Settings:Agent(  913): << traceCallingStack(): 3(ms)
D/WifiManager( 4402): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  913): doBoolean: DISCONNECT
D/WifiManager( 4402): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): TDLS: Tear down peers
I/wpa_supplicant( 1187): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4402): Radios toggled
I/jxcore-log( 4402): 
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1187): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
I/wpa_supplicant( 1187): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1187): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/Tethering(  913): interfaceLinkStateChanged wlan0, false
D/Tethering(  913): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb757fbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1187): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (0)+
D/Tethering(  913): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  913): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  913): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1187): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  913): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set ,supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  913): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  913): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/HTCRequest(  913): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  913): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1187): nl80211: Event message available
D/Tethering(  913): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  913): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1187): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  913): interfaceStatusChanged wlan0, false
D/HTCRequest(  913): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  913): WifiMonitor:getFreqFromEventString() 2462
D/WifiMonitor(  913): notifyNetworkStateChange. wifiSsid ='NG700' freq=2462
D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  913):    returned true
D/WifiPerfLock(  913): release()
D/WifiStateMachine(  913): PerfLock released for exiting ConnectedState
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  913): acquireWL(42081910): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 913 1000 null
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  913):    returned true
,D/DhcpStateMachine(  913): [RunningState] Stop DHCP
,D/libc    (  913): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  913): doBoolean: RECONNECT
D/WifiP2pService(  913): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  913): stopDataStallAlarm: current tag=20253 mDataStallAlarmIntent=PendingIntent{4321d0e8: PendingIntentRecord{425347e0 android broadcastIntent}}
D/libc    (  913): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): Fast associate: Old scan results
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiNative-wlan0(  913):    returned true
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiStateMachine(  913): Enter handleNetworkDisconnect
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  913): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  913): Provision feature enable=false
D/ConnectivityService(  913): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/UsbnetStateTracker(  913): isAvailable+-
D/UsbnetStateTracker(  913): reconnect
,D/UsbnetStateTracker(  913): isAvailable+-
D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61,
D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  913):    returned true
,D/WISPrService( 3802): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  913): default: reconnect()
D/MDST    (  913): default: setTeardownRequested(false)
D/MDST    (  913): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  913): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiP2pService(  913): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  913): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiP2pService(  913): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  913): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  913): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  913): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  913): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  913): Exit handleNetworkDisconnect
D/WISPrService( 3802): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  913): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiService(  913): New client listening to asynchronous messages
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  913): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  913): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] entry_id:4   entry:0xb7b3fe88  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7b36c20  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7b3b468  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7b3ff70  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7b3b2c8  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7b3b1c8  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb7b3fd50  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb7b3b380  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,V/NativeCrypto( 1367): Read error: ssl=0x62d4c128: I/O error during system call, Connection timed out
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  913): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  913): handleConnectivityChange: resetting
D/ConnectivityService(  913): resetConnections(wlan0, 3)
D/ConnectivityService(  913): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  913): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  913): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x62d4c128: I/O error during system call, Broken pipe
,D/WirelessDisplayService(  913): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
I//system/bin/ip(  364): RTNETLINK answers: No such process
,D/WirelessDisplayService(  913): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  913): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  913): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  913): acquireWL(43cca678): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(41f2dc30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 913 1000 null
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WISPrService( 3802): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  913): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 3802): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  913): startScan Pid: 913 Uid 1000
,D/WifiNative-wlan0(  913): doBoolean: SCAN
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  913):    returned false
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/BatSI   (  913): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  913): reportInetCondition for net -1, percentage: 0 by  (1367/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/PMS     (  913): releaseWL(43cca678): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): mActiveDefaultNetwork: -1
D/ConnectivityService(  913): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  913): releaseWL(41f2dc30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  913): releaseWL(43b19f68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/Tethering(  913): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  913): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  913): bSetPropertyMultiRAB:false
D/Tethering(  913): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  913): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  913): ipv4Default null
I/Tethering(  913): No IPv4 upstream interface, giving up.
D/Tethering(  913): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  913): DelayedCaptiveCheckState
D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  913): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
D/CaptivePortalTracker(  913): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  913): NoActiveNetworkState
,I/NetworkMonitor( 3861): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1278): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/PMS     (  913): acquireWL(4271c5b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.google.android.music (3861/10154)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.htc.launcher (1278/10076)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.docs (4248/10100)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.docs (4248/10100)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (2433/10021)
,I/ActivityManager(  913): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4468 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  913): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  913): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  913): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  913): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  913): releaseWL(4271c5b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4468): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4468): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4468): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4468): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4468): Preparing secondary program dexes.
V/DexLibLoader( 4468): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4468): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4468): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4468): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4468): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4468): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4468): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4468): Dex already copied
D/OdexVerifier( 4468): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4468): Creating class loader
,V/DexLibLoader( 4468): Finished creating class loader
V/DexLibLoader( 4468): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4468): Dex already copied
D/OdexVerifier( 4468): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4468): Creating class loader,
V/DexLibLoader( 4468): Finished creating class loader,
V/DexLibLoader( 4468): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4468): Dex already copied
D/OdexVerifier( 4468): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4468): Creating class loader,
V/DexLibLoader( 4468): Finished creating class loader,
V/DexLibLoader( 4468): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4468): Dex already copied
D/OdexVerifier( 4468): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4468): Creating class loader,
V/DexLibLoader( 4468): Finished creating class loader
,V/DexLibLoader( 4468): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4468): DexLibLoader.ensureDexLoaded took 19 ms
,W/dalvikvm( 4468): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4468): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4468): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4468): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4468): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4468): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4468): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2462 level=-54
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2462 level=-58
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1187): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1187): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1187): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462 rssi=-54
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 3
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 1
I/wpa_supplicant( 1187): wpa_s->is_screen_on 1
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): selected network = 2
D/wpa_supplicant( 1187): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb75814e8  current_ssid=0x0
D/wpa_supplicant( 1187): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1187): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1187): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1187): check if in concurrent case
,I/wpa_supplicant( 1187): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1187): RSN: PMKSA cache search - network_ctx=0xb75814e8 try_opportunistic=0
D/wpa_supplicant( 1187): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1187): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2462 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1187): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1187): nl80211: Unsubscribe mgmt frames handle 0xb7580718 (mode change)
D/wpa_supplicant( 1187): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7580718
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb7580718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb7580718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb7580718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb7580718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb7580718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb7580718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb7580718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb7580718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb7580718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb7580718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1187):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187):   * freq=2462
D/wpa_supplicant( 1187):   * Auth Type 0
D/wpa_supplicant( 1187):   * WPA Versions 0x2
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1187): nl80211: Connect request send successfully
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  913): doString: LIST_DONGLES
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  913): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (489) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-48
I/wpa_supplicant( 1187): tsf=0000000105771002
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-58
I/wpa_supplicant( 1187): tsf=0000000105771018
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-54
I/wpa_supplicant( 1187): tsf=0000000105771014
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=3
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-81
I/wpa_supplicant( 1187): tsf=0000000105771021
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  913): getDiscoveryDongleList
,D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (4) end of scan result ==
,D/WirelessDisplayService(  913): getDiscoveryDongleList
,D/WifiManager( 1227): getScanResults enter 
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/WifiStateMachine(  913): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 105771002, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2462, timestamp: 105771018, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2462, timestamp: 105771014, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 105771021, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): add 4 to mScanResults
D/BatSI   (  913): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  913): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/WifiStateMachine(  913): == begin of scan result ==
D/WifiStateMachine(  913): == (4) end of scan result ==
,W/dalvikvm( 4468): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4468): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Connect event
D/Tethering(  913): interfaceLinkStateChanged wlan0, false
D/Tethering(  913): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1187): nl80211: Associated on 2462 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Operating frequency for the associated BSS from scan results: 2462 MHz
I/wpa_supplicant( 1187): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Add randomness: count=11 entropy=4
I/wpa_supplicant( 1187): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
D/wpa_supplicant( 1187): TDLS: Remove peers on association
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1187): EAPOL: enable timer tick
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1187): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1187): Get randomness: len=32 entropy=5
,D/WifiMonitor(  913): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
D/WifiMonitor(  913): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
,D/HTCRequest(  913): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
,D/HTCRequest(  913): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
D/Tethering(  913): interfaceLinkStateChanged wlan0, true
,D/Tethering(  913): interfaceStatusChanged wlan0, true
D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/HTCRequest(  913): WifiMonitor:getFreqFromEventString() 2462
D/HTCRequest(  913): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
D/WifiMonitor(  913): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  913): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  913): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2462
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  913): Enter handleAssociatedWithEvent
D/WifiStateMachine(  913): Associated
,D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  913): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  913): Exit handleAssociatedWithEvent
I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  913): BSSID was changed, update WiFi database
,D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb75809f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48,
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1,
,I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f58b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    broadcast key
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1187): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
E/wpa_supplicant( 1187): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiApDatabaseHandler(  913): updateConnectedAP...
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1187): setConcurrentAPChannel: Set wifi.hotspot.channel to 11
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/wpa_supplicant( 1187): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=6
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1187): set send_ind_to_ndc = 0
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=1
,D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1187): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1187): EAPOL authentication completed successfully
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1187): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  913): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  913): interfaceLinkStateChanged wlan0, true
D/Tethering(  913): interfaceStatusChanged wlan0, true
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  913): updateConnectedAP...
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  913): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  913): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  913): This record is existed, only update it...
D/Tethering(  913): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,D/WifiStateMachine(  913): fetchFrequency(), freq = 2462
,D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2462, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  913): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  913): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  913): This record is existed, only update it...
,D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  913): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  913): Provision feature enable=false
D/ConnectivityService(  913): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3802): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3802): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2462, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,D/DhcpStateMachine(  913): [StoppedState] Start DHCP
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
D/WifiStateMachine(  913): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
E/FbInjectorInitializer( 4468): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/WifiStateMachine(  913): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  913): acquireWL(43bf45a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 913 1000 null
,D/WifiStateMachine(  913): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 1
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  913):    returned null
E/WifiStateMachine(  913): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  913): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  913):    returned null,
D/WifiP2pService(  913): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4263f5e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4263f5e0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,D/BluetoothManagerService(  913): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4402): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): my name is : HTC-HTC Desire 820_PT4524
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): attempting to connect to test coordinator
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): check test folder
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): found test : ./testFindPeers.js
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): found test : ./testReConnect.js
I/jxcore-log( 4402): 
,W/fb4a(:<default>):StaticBindingVerifier( 4468): Verify
,I/jxcore-log( 4402): found test : ./testSendData.js
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): Test app app.js loaded
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/Choreographer( 4402): Skipped 157 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4402): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiService(  913): New client listening to asynchronous messages
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4468): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4468): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4468): Grow heap (frag case) to 9.515MB for 73240-byte allocation
,D/Process (  913): killProcessQuiet, pid=3839
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  913): Killing 3839:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  913): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4495 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/AutoSetting( 1320): Util - no network available!
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1320): service - mHandler: cancel location update
D/AutoSetting( 1320): service -           changes count: 0
,I/ActivityManager(  913): Recipient 3839
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MobileConnectivityChangeReceiver( 4495): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4495): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4495): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4495): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  913): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4508 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  913): killProcessQuiet, pid=4114
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  913): Killing 4114:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4495/10079)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4495/10079)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4495/10079)
W/fb4a(:<default>):UserScope( 4468): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 4468): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4468): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  913): killProcessQuiet, pid=4216
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  913): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4522 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  913): Killing 4216:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  913): Recipient 4114
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Recipient 4216
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4468): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,E/dalvikvm( 4468): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4468): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/dalvikvm( 4468): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4468): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4468): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4468): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4468): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4468): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4468): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4468): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4468): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4468): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4468): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4468): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/dalvikvm( 4468): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4468): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4468): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4468): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/GAV2    ( 4522): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4468): Grow heap (frag case) to 9.932MB for 39954-byte allocation
,I/dalvikvm-heap( 4468): Grow heap (frag case) to 10.008MB for 79892-byte allocation
,I/dalvikvm-heap( 4468): Grow heap (frag case) to 10.074MB for 84664-byte allocation
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4522/10151)
,V/WebViewChromiumFactoryProvider( 4522): Binding Chromium to main looper Looper (main, tid 1) {41b2f220}
,I/LibraryLoader( 4522): Expected native library version number "",actual native library version number ""
,I/chromium( 4522): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4522): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4522): BLUETOOTH permission is missing!
D/PMS     (  913): acquireWL(4416c030): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  913): acquireWL(43c9a160): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  913): releaseWL(4416c030): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4522): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4522): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4522): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4522): Local Branch: 
I/Adreno-EGL( 4522): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4522): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4522):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4522): Starting up...
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4522/10151)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4522/10151)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (3616/10160)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (3616/10160)
,D/Process (  913): killProcessQuiet, pid=4248
,I/ActivityManager(  913): Killing 4248:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
,I/iu.Environment( 1906): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
I/iu.UploadsManager( 1906): num queued entries: 0
,I/iu.UploadsManager( 1906): num updated entries: 0
,I/iu.SyncManager( 1906): NEXT; no task
I/ActivityManager(  913): Recipient 4248
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,I/dalvikvm-heap( 4468): Grow heap (frag case) to 10.288MB for 75760-byte allocation
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,W/BroadcastQueue(  913): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43257468 u0 ReceiverList{43257348 4468 com.facebook.katana/10027/u0 remote:42f942c0}}
,W/BroadcastQueue(  913): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43257468 u0 ReceiverList{43257348 4468 com.facebook.katana/10027/u0 remote:42f942c0}}
,W/BroadcastQueue(  913): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43265eb0 u0 ReceiverList{42c405f8 4468 com.facebook.katana/10027/u0 remote:42768500}}
,D/wpa_supplicant( 1187): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1187): EAPOL: disable timer tick
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): acquireWL(43cacae8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43cacae8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4468): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4468): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/libc    (  913): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  913): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  913):    returned true
,D/WifiStateMachine(  913): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
D/WifiP2pService(  913): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  913): releaseWL(43bf45a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): gateway: /192.168.1.1
,D/WifiNative-wlan0(  913): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  913): VerifyingLinkState enter
D/WifiStateMachine(  913): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  913): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  913): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2462, Net ID: 0, Metered hint: false
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WISPrService( 3802): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiDataStallTracker(  913): startDataStallAlarm: tag=20255 delay=15s
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiWatchdogStateMachine(  913): WAN detection
V/NetworkPolicy(  913): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  913): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  913): Provision feature enable=false
D/ConnectivityService(  913): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  913): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  913): default: teardown()
D/MDST    (  913): default: setTeardownRequested(true)
D/MDST    (  913): default: setEnableApn apnType =default , enable=false
D/MDST    (  913): default: setTeardownRequested(true)
D/ConnectivityService(  913): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  913): Unexpected mtu value: android.net.wifi.WifiStateTracker@424f2be0
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  913): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  913): syncGetConfiguredNetworks
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  913): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  913): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  913): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  913): handleConnectivityChange: resetting
D/Nat464Xlat(  913): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  913): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  913): sendGeneralBroadcastDelayed, restrictEnable=false
D/WirelessDisplayService(  913): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  913):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  913): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  913): acquireWL(440fa0c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 913 1000 null
D/ConnectivityService(  913): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4495/10079)
,I/QuickSettingWifi( 1120): receive.wifiConnect:true wifiAPname:NG700 elapse:4
,D/PMS     (  913): acquireWL(430c4400): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I/CheckinService( 1906): Checkin interval check for package: unspecified last checkin: 1449063099729 min interval config: 0 actual interval: 47716
D/PMS     (  913): acquireWL(43398080): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(430c4400): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1906): Checking schedule, now: 1449063147452 next: 1449063129696
,I/CheckinService( 1906): active receiver: enabled
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1906, uid=10029, userID:0
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/CheckinService( 1906): Preparing to send checkin request
,I/EventLogService( 1906): Accumulating logs since 1449063094883
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
,D/ConnectivityService(  913): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  913): releaseWL(440fa0c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 1906): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  913): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1906): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  913): getNetworkInfo networkType=9 called by com.google.android.gms (1906/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  913): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4601 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4601): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4601): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4601): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4601): install
,I/MultiDex( 4601): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 4601): loading existing secondary dex files
,I/MultiDex( 4601): load found 3 secondary dex files
,I/MultiDex( 4601): install done
,W/dalvikvm( 4601): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4601): VFY: unable to resolve instance field 46
,W/dalvikvm( 4601): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4601): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ProviderInstaller( 4601): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4601): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4601): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4601): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 4601): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
,W/dalvikvm( 4601): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
W/dalvikvm( 4601): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4601): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1906, uid=10029, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1906, uid=10029, userID:0
,D/WearableService( 1227): callingUid 10029, callindPid: 1227
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1906, uid=10029, userID:0
E/MDM     ( 1227): [75] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/NativeLibraryUtils( 4601): Install completed successfully. count=13 extracted=0
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,D/LocationInitializer( 1906): Restart initialization of location
,D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  913): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(44132a10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1227): No location to return for getLastLocation()
,W/FusedLocationProvider( 1367): location=null
D/PMS     (  913): releaseWL(44132a10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  913): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,V/GmsCoreStatsServiceLauncher( 1906): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  913): Resuming delayed broadcast
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3513765892
,D/PMS     (  913): acquireWL(440cf4a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): releaseWL(440cf4a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WIFI_ICON( 1120): WifiActivity: 2
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  913): releaseWL(42081910): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  913): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  913): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/GpsLocationProvider(  913): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  913): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  913): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  913): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  913): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
D/PMS     (  913): acquireWL(43be1c10): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
D/PMS     (  913): releaseWL(43be1c10): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
V/Tethering(  913): bSetPropertyMultiRAB:false
,D/Tethering(  913): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  913): NoActiveNetworkState
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/Tethering(  913): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.115/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  913): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  913): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  913): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  913): Found interface wlan0
D/Tethering(  913): TetherMasterSM: InitialState processMessage what=3
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1626544959
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 3861): type=WIFI subType= reason=null isConnected=true
,I/ConnectivityHelper( 1278): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.musicenhancer (3896/10053)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4495/10079)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.htc.launcher (1278/10076)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.google.android.music (3861/10154)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  913): DelayedCaptiveCheckState
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
D/PMS     (  913): acquireWL(41d74700): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(41d74700): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (2433/10021)
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4495): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4495): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1320): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1320): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1320): service - handleMessage() setting current location null
,D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4522/10151)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AutoSetting( 1320): service - onStartCommand() check timezone in 30000
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  371): CdmEngine::CloseSession
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (3616/10160)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (3616/10160)
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1906, uid=10029, userID:0
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
I/iu.Environment( 1906): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
I/iu.UploadsManager( 1906): num queued entries: 0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/iu.UploadsManager( 1906): num updated entries: 0
I/iu.SyncManager( 1906): NEXT; no task
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  913): BroadcastRSSIForIMS, newrssi =-53 , oldRssi= -200
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,I/CheckinService( 1906): Checkin interval check for package: unspecified last checkin: 1449063099729 min interval config: 0 actual interval: 48814
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
D/PMS     (  913): acquireWL(42537600): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(42537600): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  913): acquireWL(4272ba40): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1367): [NET] getaddrinfo-, 1
,D/libc    ( 1367): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =dd1a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,I/PMS     (  913): Going to sleep due to screen timeout...
,I/ActivityManager(  913): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421c6a08
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  913): disable: get sensor name = CM36282 Light sensor
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421c6a08, eanble = 0, strlen(mName) = 59
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  913): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42417518
W/SensorService(  913): Listener[1] = com.htc.smartdim.sensor_eye@4243bf60
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  913): Couldn't get kernel wake lock stats
V/LightsService(  913): setLight #2: color=#0
D/qdlights(  913): set_light_buttons_func: on=0 brightness=0
V/LightsService(  913): setLight #0: color=#0
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 249
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1367): [NET] getaddrinfo_proxy-, success
,I/Adreno-EGL( 4601): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4601): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4601): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4601): Local Branch: 
I/Adreno-EGL( 4601): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4601): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4601):                  aa63bbd948f41d15fc72f585e
D/WirelessDisplayService(  913): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  913): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  913): mWirelessDisplayManager is null
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,W/fb4a(:<default>):UserScope( 4468): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4468): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=60 [5][3][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  913): acquireWL(43c8f5d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (4601/10029)
,W/Settings( 4601): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
D/PMS     (  913): releaseWL(4272ba40): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  913): handleInetConditionChange: starting a change hold
,I/Adreno-EGL( 4601): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4601): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4601): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4601): Local Branch: 
I/Adreno-EGL( 4601): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4601): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4601):                  aa63bbd948f41d15fc72f585e
D/PMS     (  913): releaseWL(43c8f5d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(43d46a90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  913): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  913): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
D/PMS     (  913): releaseWL(43d46a90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/Adreno-EGL( 4601): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4601): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4601): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4601): Local Branch: 
I/Adreno-EGL( 4601): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4601): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4601):                  aa63bbd948f41d15fc72f585e
,D/SurfaceControl(  913): Excessive delay in blankDisplay() while turning screen off: 317ms
,E/fb4a(:<default>):LocalFbBroadcastManager( 4468): Called registerBroadcastReceiver twice.
D/NfcService( 1261): ScreenObserver: OFF
D/NfcService( 1261): applyRouting - 0
D/PMS     (  913): nativeSetInteractive:false
D/PMS     (  913): nativeSetInteractive:false done
D/PMS     (  913): nativeSetAutoSuspend:true
D/PMS     (  913): nativeSetAutoSuspend:true done
D/HABCtrl (  913): TPE algorithm. remove timeout.
I/InputManager(  913): Cancel all due to getting PMS screen off broadcast
D/PMS     (  913): OOBE c monitor 11
I/InputMethodManagerService(  913): screenObserver, isScreenOn=false
I/InputMethodManagerService(  913): Disable input method client, pid=4402
,D/NfcService( 1261): applyRouting -2
,V/KeyguardServiceDelegate(  913): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43d4c288)
,I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  913): **** SHOWN CALLED ****
W/ResourceType( 4402): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4402): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b421d0 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMS     (  913): acquireWL(43c40670): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1261 1027 null
D/PMS     (  913): releaseWL(43c40670): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  913): wakingUp
I/WindowManager(  913): No lock screen! windowToken=null
,D/PMN     (  913): onScreenOn
D/WirelessDisplayService(  913): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): acquireWL(42f2ba30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
D/PMS     (  913): releaseWL(42f2ba30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
D/PowerUI ( 1120): closing low battery warning: level=100
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,D/MtpService( 2433): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1261): applyRouting - 0
,D/MtpService( 2433): [MTP][onReceive]-
,I/HtcPowerSaver(  913): << updateStatus
,D/AutoSetting( 1320): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1261): applyRouting -2
D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_ON
D/PMS     (  913): acquireWL(432fe128): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1261 1027 null
D/PMS     (  913): releaseWL(432fe128): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  913): ACTION_SCREEN_ON
I/AlarmManager(  913): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  913): [AlarmQueuing] done recovering
I/AlarmManager(  913): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  913): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  913): startDataStallAlarm: tag=20256 delay=15s
D/TetherSettings( 3802): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3802): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3802): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3802): Cust_ConnectToPC   : spcsc>false
D/        ( 3802): Cust_ConnectToPC   : IPT>true
D/        ( 3802): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3802): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3802): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3802): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3802): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/ClockThread( 1120): stop update clock
D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): SET_SCREEN_ON:On
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  913):    returned true
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/PSReceiver( 3802): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,W/ContextImpl( 3802): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=33 [6][2][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/SmartNS_PSService( 3802): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3802): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3802):  defaultType:0
D/WIFI_ICON( 1120): WifiActivity: 3
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED 3 -> 3
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/NetworkPolicy(  913): updateScreenOn: false
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,I/ActivityManager(  913): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4648 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  913): acquireWL(438f45d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(438f45d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 4468): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4468): [NET] getaddrinfo-,err=8
D/libc    ( 4468): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4468): [NET] getaddrinfo-, 1
,D/libc    ( 4468): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =917a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/WifiStateMachine(  913): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  913): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 2
D/libc    (  364): [NET]res_nsend:resplen=74
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4468): [NET] getaddrinfo_proxy-, success
I/global  ( 4468): call createSocket() return a new socket.
D/libc    ( 4468): [NET] getaddrinfo+,hn 11(0x33312e31332e39),sn(),family 0,flags 4
,D/libc    ( 4468): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  913): acquireWL(43360338): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  913): releaseWL(43360338): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1780): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1780): onScreenOn: 1449063149208
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1780): onScreenOn: 1449063149208
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42417518
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
D/SmartSyncUtils( 4648): isEpsOn(), nState = 0
W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42417518, eanble = 0, strlen(mName) = 91
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  913): Listener[0] = com.htc.smartdim.sensor_eye@4243bf60
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/CheckinRequestBuilder( 1906): Classify the device as Phone.
D/PMS     (  913): acquireWL(42d0ba38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4648 1000 null
D/PMN     (  913): goingToSleep
D/PMS     (  913): acquireWL(43a8cf90): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 913 1000 null
,D/PMS     (  913): releaseWL(42d0ba38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/AlarmManager(  913): ACTION_SCREEN_OFF
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
I/AlarmManager(  913): [AlarmQueuing] screen off now: 
I/AlarmManager(  913): [AlarmQueuing] data connection: true
I/AlarmManager(  913): [AlarmQueuing] wifi connection: true
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  913): stopDataStallAlarm: current tag=20256 mDataStallAlarmIntent=PendingIntent{438570a0: PendingIntentRecord{425347e0 android broadcastIntent}}
,D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): SET_SCREEN_ON:Off
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): get_ip_address source addr = c0a80173
I/wpa_supplicant( 1187): htc_wext_set_keepalive gateway addr = c0a80101
D/WifiNative-wlan0(  913): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
D/PMS     (  913): releaseWL(43a8cf90): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): acquireWL(4263cdc0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 913 1000 null
D/WifiNative-wlan0(  913):    returned true
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
V/SRS_Proc(  371): ParamSet string: screen_state=off
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4648): getMobilePolicyEnabled, result = true
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  913):    returned true
D/NetworkPolicy(  913): updateScreenOn: false
,D/PMS     (  913): releaseWL(4263cdc0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1249): start background delete task...
,D/Process (  913): killProcessQuiet, pid=4274
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ContactMessageStore( 1249): size: 0 , 0
,D/ContactMessageStore( 1249): Background delete complete
I/ActivityManager(  913): Killing 4274:com.htc.backup/1000 (adj 15): empty #17
,D/libc    ( 1906): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1906): [NET] getaddrinfo-,err=8
D/libc    ( 1906): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1906): [NET] getaddrinfo-, 1
,D/libc    ( 1906): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5bb7 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 4274
W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=40 [5][2][0]
,D/SmartSyncUtils( 4648): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4648): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4648): isEpsOn(), nState = 0
D/WifiService(  913): New client listening to asynchronous messages
,D/PMS     (  913): releaseWL(43c9a160): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4243bf60
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 1
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4243bf60, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 0
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4243bf60, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4243bf60
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 248
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1906): [NET] getaddrinfo_proxy-, success
E/ActivityThread(  913): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426a7348 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426a7348 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  913): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  913): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  913): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  913): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  913): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  913): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  913): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  913): 	at dalvik.system.NativeStart.main(Native Method)
,D/AutoSetting( 1320): service - mHandler: cancel location update
,D/AutoSetting( 1320): service -           changes count: 0
,D/PMS     (  913): acquireWL(43716c50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1906): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1906): [NET] getaddrinfo-,err=8
D/PMS     (  913): releaseWL(43716c50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(43d0f460): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] getTotalRam: 1873 Mb
D/PMS     (  913): releaseWL(43d0f460): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=14 [7][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1780): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1780): onScreenOff
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1780): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1780): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1780): onScreenOff
D/libc    ( 1906): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1906): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
D/libc    ( 1906): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1906): [NET] getaddrinfo-,err=8
,D/PMS     (  913): acquireWL(43c97228): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4468 10027 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/CheckinTask( 1906): Sending checkin request (12177 bytes)
,D/libc    ( 4468): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4468): [NET] getaddrinfo-,err=8
,I/dalvikvm-heap( 4468): Grow heap (frag case) to 10.980MB for 32784-byte allocation
,I/dalvikvm-heap( 4468): Grow heap (frag case) to 11.006MB for 32784-byte allocation
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4468/10027)
,I/CheckinRequestBuilder( 1906): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  913): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1906): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  913): getNetworkInfo networkType=9 called by com.google.android.gms (1906/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=15 [20][3][0]
,I/CheckinRequestBuilder( 1906): Classify the device as Phone.
,I/CheckinTask( 1906): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1906): Checking schedule, now: 1449063149969 next: 1449586086962
,I/CheckinService( 1906): active receiver: disabled
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1906, uid=10029, userID:0
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,I/CheckinService( 1906): Checking schedule, now: 1449063149992 next: 1449586086962
,I/CheckinService( 1906): active receiver: disabled
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1906, uid=10029, userID:0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
,D/CheckinService( 1906): Recording last checkin time for package unspecified as 1449063149997
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
D/PMS     (  913): releaseWL(43398080): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=100 [1][1][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
D/PMS     (  913): acquireWL(440fcb38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
D/PMS     (  913): releaseWL(440fcb38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-,err=8
D/libc    (  913): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  913): [NET] getaddrinfo-, 1
,D/libc    (  913): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =bc00 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  913): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  913): Find DNS Address www.htc.com/104.81.130.175
,I/jxcore-log( 4402): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4402): 
,I/global  ( 4468): I/O error closing connection
I/global  ( 4468): java.net.SocketException: Socket is closed
I/global  ( 4468): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4468): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4468): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4468): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4468): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4468): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4468): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4468): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4468): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4468): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4468): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4468): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4468): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4468): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4468): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4468): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4468): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4468): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4468): Removing a connection that never existed!
D/PMS     (  913): releaseWL(43c97228): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/GAV2    ( 4522): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/ContactMessageStore( 1249): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1249): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  913): killProcessQuiet, pid=4235
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4235:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4235
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1531): service - handleMessage() stop self
,D/AutoSetting( 1531): service - onDestroy() END
,D/AutoSetting( 1531): service - handleMessage() quit looper
,D/Process (  913): killProcessQuiet, pid=4292
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4292:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4292
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  913): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4684 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1278): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "sms"
,I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/Launcher( 1278): Deferring update until onResume
D/Launcher( 1278): waitUntilResume // bindAppsUpdated
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,W/SystemReader( 1261): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,D/PhoneApp( 1249): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4684): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4684): MmsConfig.loadMmsSettings
,W/dalvikvm( 4684): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4684): VFY: unable to resolve instance field 46
,W/dalvikvm( 4684): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4684): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  913): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4707 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4684, uid=10111, userID:0
,W/Settings( 4684): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4684, uid=10111, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4684, uid=10111, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4684, uid=10111, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4684, uid=10111, userID:0
,D/MessageFrequencyProvider( 4707): onCreate
D/MmsCustomizationProvider( 4707): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4707): GetPrviateResource
,V/GetPrviateResource( 4707): GetPrviateResource
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4684, uid=10111, userID:0
D/PMS     (  913): acquireWL(43d30c38): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4684 10111 null
,D/MmsCustomizationProvider( 4707): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2822): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Babel   ( 4684): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4684): MmsConfig.loadFromDatabase
,W/PackageManager(  913): Unable to load service info ResolveInfo{44171ef0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  913): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  913): acquireWL(43b1a8d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3616 10160 null
,D/PMS     (  913): acquireWL(439bfa88): PARTIAL_WAKE_LOCK  Icing 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43b1a8d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,E/Babel   ( 4684): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4684): MmsConfig.loadFromResources
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,E/Babel   ( 4684): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4684): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/MessageCustFlag( 4707): sense_version=6.0
,D/BTAccessoryUtil( 4707): createReceiver
,D/BTAccessoryUtil( 4707): registerReceiver return intent = null
D/MessageCustFlag( 4707): sku_id=99
,W/SystemReader( 4707): Cannot find message_ambs_application_id, use default value instead
,D/PMS     (  913): releaseWL(43d30c38): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ProviderInstaller( 4684): Installed default security provider GmsCore_OpenSSL
D/Messaging( 4707): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4707): networkCode: 
D/MessageCustFlag( 4707): sku_id=99
D/MmsConfig( 4707): SIE smsPri: null
,D/MmsConfig( 4707): networkCode: 
D/HtcTelephonyCapability( 4707): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4707): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4707): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4707): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  913): Resuming delayed broadcast
,D/Process (  913): killProcessQuiet, pid=4318
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  913): Killing 4318:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  913): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  913): Recipient 4318
,D/WifiService(  913): Client connection lost with reason: 4
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 1906): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1906): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1906): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  913): releaseWL(439bfa88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(4240de38): PARTIAL_WAKE_LOCK  Icing 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  913): releaseWL(4240de38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  913): acquireWL(424320d8): PARTIAL_WAKE_LOCK  Icing 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(424320d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(4209efe8): PARTIAL_WAKE_LOCK  Icing 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
,D/RemoteDisplayProvider(  913): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,V/GmsNetworkLocationProvi( 1227): DISABLE,
D/RemoteDisplayProvider(  913): start
,I/GCoreNlp( 1227): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  913): releaseWL(4209efe8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(4254eda0): PARTIAL_WAKE_LOCK  Icing 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(42512590): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42512590): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(44196988): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(4254eda0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(44196988): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42660eb8): PARTIAL_WAKE_LOCK  Icing 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(425f1578): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(425f1578): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42660eb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(423561d0): PARTIAL_WAKE_LOCK  Icing 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(423561d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2822): UpdateCorporaTask done [took 426 ms] updated apps [took 426 ms] 
,D/CaptivePortalTracker(  913): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  913): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  913): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41bc2d10 +
,I/Prism.WidgetManager( 1278): onLoadItems() +
,D/Process (  913): killProcessQuiet, pid=3896
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3896:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3896
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Prism.WidgetManager( 1278): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1278): onLoadItems() -
,I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41bc2d10 -
,D/PhoneApp( 1249): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1249): -- N1 =0
,D/PhoneApp( 1249): -- N2 =0
,D/PhoneApp( 1249): -- N3 =0
,D/Messaging( 4707): mNeedToUpdateDate2 start
,D/MmsConfig( 4707): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4707): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4707): 
D/MmsAsyncWorkHandler( 4707): HM tk = 20001
D/SettingsManager( 4707): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b3c610
,D/ReportIndicatorCache( 4707): MSG_QUERY_REPORTS >>
,I/Messaging( 4707): mccmnc> 
,D/TelephUtils( 1249): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/DraftCache( 4707): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4707): [DraftCache/1] refresh
D/MmsSmsV2Provider( 1249):  phoneType = -1
,D/MmsSmsV2Provider( 1249): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MmsConfig( 4707): networkCode: 
,D/Messaging( 4707): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1249): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1249):  phoneType = -1
,D/MmsSmsV2Provider( 1249): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4707): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4707): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4707): createReceiver
,D/MessageCustFlag( 4707): sense_version=6.0
,D/Jerry   ( 4707): start to preload cursor >>>>>>>
,D/TelephUtils( 1249): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1249): Update uri=content://mms, match=0
,V/MmsProvider( 1249): selection=st=129 AND m_type!=134
,D/Messaging( 4707): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4707): TransactionService is going to be woken up.
D/TelephUtils( 1249): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1249): sku_id=99
,V/TransactionService( 4707): 1-Creating TransactionService
,D/DraftCache( 4707): [DraftCache/463] rebuildCache
,D/TelephUtils( 1249): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
V/TransactionService( 4707): onStartCommand: 1
D/MmsSystemEventReceiver( 4707): unRegisterForConnectionStateChanges
D/MmsSmsV2Provider( 1249):  phoneType = -1
,D/MmsSmsV2Provider( 1249): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
V/TransactionService( 4707): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4707): Loading previous transactions.
,D/Messaging( 4707): mNeedToUpdateDate2: false
,D/TelephUtils( 1249): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1249): device_type: 1
,D/TelephUtils( 1249): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/TransactionService( 4707): Force set service start id to 1
V/TransactionService( 4707): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4707): unRegisterForConnectionStateChanges
,D/MmsSmsV2Provider( 1249):  phoneType = -1
D/TransactionService( 4707): stopSelfResult: true, mLastHandledServiceId: 1
,D/MmsSmsV2Provider( 1249): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,V/TransactionService( 4707): Destroying TransactionService
,V/TransactionService( 4707): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/Messaging( 4707): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1249): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1249):  phoneType = -1
,D/TelephUtils( 1249): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/Jerry   ( 1249): URI_DRAFT
D/Messaging( 4707): ViewCache CreatePreload
,D/Messaging( 4707): ViewCache CreatePreloadOnlyMultipleOpsList
,D/DraftCache( 4707): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4707): [DraftCache/463] rebuildCache time: 2
D/MmsAsyncWorkHandler( 4707): 
D/MmsAsyncWorkHandler( 4707): HM tk = 20002
,D/Cust_MMSMS( 4707): _has_set_default_values_2=true
,D/TelephUtils( 1249): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1249): sku_id=99
,D/MsgPreferenceUtils( 4707): def_index: 0
,D/MsgPreferenceUtils( 4707): globalIndex = 1
D/MsgPreferenceUtils( 4707): phone state: true
D/MsgPreferenceUtils( 4707): sd state: false
,D/MsgPreferenceUtils( 4707): vIndex = 0
,D/TelephUtils( 1249): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1249): sku_id=99
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4684): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(435fc270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): releaseWL(435fc270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/AutoSetting( 1320): service - mHandler: update timezone
,D/AutoSetting( 1531): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  913): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1531): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1531): service - onCreate()
W/ActivityManager(  913): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1531): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1531): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1572): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1531): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1531): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1531): service - mHandler: update timezone
,D/AutoSetting( 1531): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1531): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1531): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1531): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1120): removeNotification.gc:54
,I/RemoteViews( 1120): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41edaca0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.htclocationservice 3 7 1 11
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
,D/PMS     (  913): acquireWL(43c7dda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=140443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43c7dda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(43266a20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,V/AlarmManager(  913): sending alarm PendingIntent{441119f0: PendingIntentRecord{426ba8e8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=139811, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{43d3f300: PendingIntentRecord{4240f0d8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=140503, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{42316cf8: PendingIntentRecord{42323500 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141789, Int=0
,D/PMS     (  913): acquireWL(43c27880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=19 [21][4][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(433774d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43c27880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(433774d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4325e4d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): releaseWL(4325e4d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(434108d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/GpsLocationProvider(  913): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  913): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  913): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  913): acquireWL(431c9980): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
D/PMS     (  913): releaseWL(43266a20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  913): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-,err=8
D/libc    (  913): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  913): [NET] getaddrinfo-, 1
,D/libc    (  913): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =24d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): acquireWL(43d284c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(44266048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(434108d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/VacuumService( 1367): Vacuum at: now=1449063181548 tag=VacuumService
,D/PMS     (  913): releaseWL(44266048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42719fc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43d284c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): releaseWL(42719fc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(43d2ff80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): releaseWL(43d2ff80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(438e6b48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): releaseWL(438e6b48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  913): [NET] getaddrinfo_proxy-, success
I/global  (  913): call createSocket() return a new socket.
D/libc    (  913): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  913): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  913): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  913): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  913):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  913): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/Process (  913): killProcessQuiet, pid=4339
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4339:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4339
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): releaseWL(431c9980): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1249): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1249): MSG_NOTIFY_CS_TO_SYNC <<
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{42c10a08 u0 com.htc.htclocationservice/.AutoSettingService}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/AutoSetting( 1531): service - handleMessage() stop self
,D/AutoSetting( 1531): service - onDestroy() END
,D/AutoSetting( 1531): service - handleMessage() quit looper
,D/Process (  913): killProcessQuiet, pid=4353
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4353:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4353
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(43cb3728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  913): runPSCheck
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PMS     (  913): releaseWL(43cb3728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/TelephonyReceiver( 1249): switchBindHtcMsgCursor: null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(4393f490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(4393f490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1120): closing low battery warning: level=100
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(42ac9898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=200443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42ac9898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(438e3dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10027}
,V/AlarmManager(  913): sending alarm PendingIntent{437cd6f8: PendingIntentRecord{438063c8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226899, Int=0
,I/ActivityManager(  913): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4778 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  913): sending alarm PendingIntent{4243d720: PendingIntentRecord{4268e0b0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449063252281, Int=10800000
,D/PMS     (  913): releaseWL(438e3dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.aurora (4778/10049)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/Process (  913): killProcessQuiet, pid=4086
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4086:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4086
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ClearcutLoggerApiImpl( 1367): disconnect managed GoogleApiClient
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(44244fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(44244fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,D/PMS     (  913): acquireWL(43d4cb30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10027}
,V/AlarmManager(  913): sending alarm PendingIntent{439c0af8: PendingIntentRecord{438063c8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229678, Int=0
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
D/PMS     (  913): releaseWL(43d4cb30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(4416b8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4416b8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(4279d298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=260443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4279d298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43d29cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43d29cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(42614c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42614c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(44110850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=320443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(44110850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43325a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1120): closing low battery warning: level=100
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): releaseWL(43325a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(432e3108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(432e3108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/HtcPowerSaver(  913): >> updateStatus
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(4399d590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=380443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4399d590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43986b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43986b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/HtcPowerSaver(  913): >> updateStatus
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(44122dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(44122dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(439c95b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=440443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(439c95b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(437a7e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PMS     (  913): releaseWL(437a7e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43929998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=500443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): releaseWL(43929998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(421e5dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10027}
,V/AlarmManager(  913): sending alarm PendingIntent{431c5c60: PendingIntentRecord{433107e8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=409433, Int=300000
,V/AlarmManager(  913): sending alarm PendingIntent{41e07a50: PendingIntentRecord{42562c98 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=536445, Int=0
,D/PMS     (  913): acquireWL(4264b590): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 913 1000 null
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): releaseWL(421e5dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42685af0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=9 [171][16][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): acquireWL(433778e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 913 1000 WorkSource{10160}
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): acquireWL(43c50218): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 913 1000 WorkSource{10029}
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(4264b590): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  913): releaseWL(42685af0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/PMS     (  913): acquireWL(44136218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(44136218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): acquireWL(4270b188): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(4270b188): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): acquireWL(42c104f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(42c104f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 1227): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): acquireWL(426256f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(433778e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  913): releaseWL(426256f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): acquireWL(42670b38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(43c50218): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  913): releaseWL(42670b38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43c66268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(43c66268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43c2f230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=560443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43c2f230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43ca3a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41e07a50: PendingIntentRecord{42562c98 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=566569, Int=0
,D/PMS     (  913): acquireWL(43d34a00): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 913 1000 null
,D/PMS     (  913): releaseWL(43ca3a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): acquireWL(43d119e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(43d34a00): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  913): releaseWL(43d119e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(433042a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(433042a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(427805a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(427805a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43cd5d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=620443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43cd5d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/ContactMessageStore( 1249): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1249): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1249): sku_id=99
D/ContactMessageStore( 1249): start background delete task...
,D/ContactMessageStore( 1249): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1249): size: 0 , 0
,D/ContactMessageStore( 1249): Background delete complete
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/Process (  913): killProcessQuiet, pid=4446
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4446:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4446
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43333108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(43333108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(432ce6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=680443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(432ce6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43650ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10027}
,V/AlarmManager(  913): sending alarm PendingIntent{431c5c60: PendingIntentRecord{433107e8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=709433, Int=300000
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): releaseWL(43650ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43307548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43307548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(440f77a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=740443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1278): Grow heap (frag case) to 12.600MB for 50416-byte allocation
D/PMS     (  913): releaseWL(440f77a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(42c95d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42c95d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43f3ef00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,D/ConnectivityService(  913): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  913): sending alarm PendingIntent{41e36690: PendingIntentRecord{424fd398 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784257, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{428c32b8: PendingIntentRecord{42d379d0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449063815584, Int=1800000
,D/PMS     (  913): acquireWL(435c67b0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): Done.
,D/ConnectivityService(  913): Setting timer for 720seconds
,D/PMS     (  913): releaseWL(43f3ef00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  913): acquireWL(43788880): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(435c67b0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 1906): Aggregate from 1449063147482 (log), 1449062015455 (data)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): releaseWL(43788880): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms},
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(438dffa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(438dffa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43ce7178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=800443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43ce7178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43de38c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43de38c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43c68688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43c68688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(4412fb50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=860443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4412fb50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43c645e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43c645e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43c004b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=920443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1278): Grow heap (frag case) to 12.600MB for 50416-byte allocation
,D/PMS     (  913): releaseWL(43c004b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(440aa7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
,D/PMS     (  913): releaseWL(440aa7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43c35fc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(43c35fc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/HtcPowerSaver(  913): >> updateStatus
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(440b3c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=980443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(440b3c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(432f18b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{432f3738: PendingIntentRecord{41cd0e98 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1009313, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{42180658: PendingIntentRecord{4274a358 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449063972691, Int=900000
,V/AlarmManager(  913): sending alarm PendingIntent{427381e8: PendingIntentRecord{43c35668 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449064049298, Int=0
,D/PMS     (  913): acquireWL(43c1dce0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43c1dce0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4648): call getInstance()
,D/SmartSyncUtils( 4648): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4648): MY_DEBUG = false
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,D/PMS     (  913): acquireWL(43cf9228): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(442a2390): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=5 [154][8][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/SmartSyncScreenOnOffTimeReceiver( 4648): [updateNmRange] bManual = false
D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  913): handleInetConditionChange: starting a change hold
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/PMS     (  913): acquireWL(441a6ab0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4648 1000 null
D/PMS     (  913): releaseWL(432f18b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/SmartSyncScreenOnOffTimeReceiver( 4648): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4648): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4648): SettingOnTime = 1449122400000, randomSettingOnTime = 1449119559000
,D/SmartSyncScreenOnOffTimeReceiver( 4648): SettingOffTime = 1449108000000, randomSettingOffTime = 1449111862000
D/SmartSyncScreenOnOffTimeReceiver( 4648): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4648): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4648): bNightModeTurnOffOnce = false
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): releaseWL(442a2390): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(441a6ab0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,D/PMS     (  913): acquireWL(41e08e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(433399b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,D/UdcCache:FPQuery( 1906): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  913): releaseWL(43cf9228): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
W/BatSI   (  913): Couldn't get kernel wake lock stats
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/GetConfigurationSnapshotOperation( 1367): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(433399b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(436326d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
D/PMS     (  913): releaseWL(436326d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/PhenotypeFlagCommitter( 1367): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1367): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  913): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/GetCommittedConfigurationOperation( 1367): no corresponding serverToken: com.google.android.gms.playlog.uploader
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/libc    ( 1367): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1367): [NET] getaddrinfo-, 1
V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x662b7008: I/O error during system call, Connection timed out
D/libc    ( 1367): [NET] getaddrinfo_proxy+
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8b92 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 157
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1367): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1367): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=14 [7][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
W/Uploader( 1367):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1367): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/GetCommittedConfigurationOperation( 1367): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/GetCommittedConfigurationOperation( 1367): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): releaseWL(41e08e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(432d0590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): releaseWL(432d0590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4371f2f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023385
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024288
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024296
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024300
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027133
,D/PMS     (  913): releaseWL(4371f2f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4270e608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/HeadsetPhoneState( 1633): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/DotMatrix( 1572): [EventService] reorderNotification, total:1
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
V/NotificationService(  913): batLight: plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=98
V/LightsService(  913): setLight #8: color=#c80000
D/qdlights(  913): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/PMS     (  913): releaseWL(4270e608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/qdlights(  913): [LedInfo] has indicator attribute
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3802): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3802): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3802): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3802): Cust_ConnectToPC   : spcsc>false
D/        ( 3802): Cust_ConnectToPC   : IPT>true
,D/        ( 3802): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3802): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3802): Index of the first 1 = -1
W/Settings( 3802): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3802): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3802): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3802): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3802): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3802): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(440be9e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(440be9e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/HtcPowerSaver(  913): >> updateStatus
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(42668e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42668e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(43281a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1040443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43281a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(433b2808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(433b2808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(4249ae30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1100443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4249ae30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(42625748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42625748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(4340a578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1160443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1278): Grow heap (frag case) to 12.648MB for 50416-byte allocation
,D/PMS     (  913): releaseWL(4340a578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43bbbe50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43bbbe50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(431d7510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(431d7510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=99
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  913): updateBatteryInfo
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(4331fc40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1220443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4331fc40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(425cee40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(425cee40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43c009c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1280443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43c009c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43291d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43291d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43898dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1340443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1278): Grow heap (frag case) to 12.649MB for 50416-byte allocation
,D/PMS     (  913): releaseWL(43898dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(432def20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(432def20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43c89ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1400443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43c89ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(43361540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43361540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,D/HeadsetPhoneState( 1633): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/DotMatrix( 1572): [EventService] reorderNotification, total:0
V/NotificationService(  913): batLight: Full, plugged
D/HtcPowerSaver(  913): updateBatteryInfo
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3802): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3802): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3802): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3802): Cust_ConnectToPC   : spcsc>false
D/        ( 3802): Cust_ConnectToPC   : IPT>true
D/        ( 3802): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3802): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3802): Index of the first 1 = -1
W/ContextImpl( 3802): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3802): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3802): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3802): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3802): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(4371e088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4371e088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43d20e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1460443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43d20e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43361c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): releaseWL(43361c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(42785da8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1520443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42785da8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43c4fa40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43c4fa40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(432e42d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(432e42d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(4331ae78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1580443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1278): Grow heap (frag case) to 12.649MB for 50416-byte allocation
,D/PMS     (  913): releaseWL(4331ae78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(438ced70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(438ced70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43d1bf88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43d1bf88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43bb5c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1640443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43bb5c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43318dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(43318dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(44166548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1700443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(44166548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(431c0098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(431c0098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(4269e6e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
D/PMS     (  913): releaseWL(4269e6e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(439c99a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1760443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(439c99a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43333b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43333b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(427064a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1820443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  913): Prepared write state in 39ms
,D/PMS     (  913): releaseWL(427064a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  913): Pruning old procstats: /data/system/procstats/state-2015-12-01-17-48-24.bin
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(43c40188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,D/ConnectivityService(  913): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  913): sending alarm PendingIntent{41e36690: PendingIntentRecord{424fd398 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1504281, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{42071920: PendingIntentRecord{42629da0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821246, Int=1800000
,D/PMS     (  913): acquireWL(438005f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 913 1000 null
V/AlarmManager(  913): sending alarm PendingIntent{433e9738: PendingIntentRecord{4340b908 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1850348, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{42180658: PendingIntentRecord{4274a358 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449064872691, Int=900000
,D/ConnectivityService(  913): Done.
,D/ConnectivityService(  913): Setting timer for 720seconds
,D/PMS     (  913): releaseWL(438005f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/LocationManagerService(  913): getAllProviders()=[passive, gps, network]
W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  913): releaseWL(43c40188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/BatSI   (  913): Couldn't get kernel wake lock stats
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(432233e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(432233e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,D/PMS     (  913): acquireWL(42632440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b3fe28: PendingIntentRecord{41d26cb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1880443, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42632440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4402): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4847): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4847): ====startRecUseTime====
D/htc.customization.log.level( 4847):  is 
W/CustomizationLogLevel( 4847): Level value is invalid, use default level 2
D/CustomizationManager( 4847):  Read ACC file spent 0.090 (s)
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4847): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4847): Parsing tag category name = system
I/CustomizationCIDLoader( 4847): Parsing tag category name = application
I/CustomizationCIDLoader( 4847): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4847): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4847): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4847): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4847): Parsing tag category name = Settings
D/CustomizationManager( 4847):  Read CID file spent 0.131 (s)
D/CustomizationManager( 4847):  All configurations done spent 0.131 (s)
W/HtcNativeFlag( 4847): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4847): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4847): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4847): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  913): deletePackageAsUser: pkg=com.test.thalitest, pid=4847, uid=2000 user=0
I/ActivityManager(  913): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  913): killProcessQuiet, pid=4402
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  913): Killing 4402:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  913): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  913): killProcessQuiet, pid=4522
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  913): killProcessQuiet, pid=4508
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  913): killProcessQuiet, pid=4495
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  913): killProcessQuiet, pid=3861
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  913): Killing 4522:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  913): Killing 4508:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  913): Killing 4495:com.google.android.setupwizard/u0a79 (adj 15): empty for 1802s
I/ActivityManager(  913): Killing 3861:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
I/ActivityManager(  913):   Force finishing activity ActivityRecord{41e57e08 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  913): Recipient 4508
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 4522
I/ActivityManager(  913): Recipient 4495
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  913): Copying FileAsset 0x5cad8448 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  913): WIN DEATH: Window{424d8d58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  913): Client connection lost with reason: 4
W/Binder  ( 1213): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1213): java.lang.NullPointerException
W/Binder  ( 1213): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1213): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1213): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1213): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  913): Got RemoteException sending setActive(false) notification to pid 4402 uid 10389
I/ActivityManager(  913): Recipient 3861
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  913): Client com.google.android.music (pid 3861): Died!
W/PackageSettings(  913): Skipping PackageSetting{42306b88 com.example.hello/10396} due to missing metadata
I/ActivityManager(  913): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1227): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  913): acquireWL(43c54030): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(43c54030): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1303): Cleaning up data for package: com.test.thalitest
I/Launcher( 1278): Deferring update until onResume
D/Launcher( 1278): waitUntilResume // bindAppsRemoved
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
W/SystemReader( 1261): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1278): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/IcingCorporaProvider( 2822): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/InputMethodManagerService(  913): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/ActivityManager(  913): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4863 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
W/Parcel  ( 1261): Reading a NULL string not supported here.
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
E/ExternalAccountType( 1342): Unsupported attribute readOnly
D/PhoneApp( 1249): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  913): acquireWL(43c04608): PARTIAL_WAKE_LOCK  Icing 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(43c04608): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(43baf6f8): PARTIAL_WAKE_LOCK  Icing 0x1 1906 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2822): UpdateCorporaTask done [took 397 ms] updated apps [took 397 ms] 
W/FileUtils( 4863): Failed to chmod(/data/data/com.google.android.apps.docs/databases/ClientFlag.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteDatabase( 4863): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4863): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4863): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4863): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4863): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4863): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4863): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4863): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4863): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4863): threadid=11: thread exiting with uncaught exception (group=0x416fde30)
E/AndroidRuntime( 4863): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4863): Process: com.google.android.apps.docs, PID: 4863
E/AndroidRuntime( 4863): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4863): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4863): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4863): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4863): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4863): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4863): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4863): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4863): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  913): App crashed! Process: com.google.android.apps.docs
E/SQLiteDatabase( 4863): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4863): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4863): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4863): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4863): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4863): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4863): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4863): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4863): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4863): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4863): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4863): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4863): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4863): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4863): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4863): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4863): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4863): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4863): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4863): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4863): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4863): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4863): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4863): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4863): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4863): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4863): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4863): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4863): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4863): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4863): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4863): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4863): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4863): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4863): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4863): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4863): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4863): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4863): Opened ClientFlag.db in read-only mode
D/Process ( 4863): killProcess, pid=4863
D/Process ( 4863): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  913): Can't write: system_app_crash
E/DropBoxManagerService(  913): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  913): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  913): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  913): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  913): 	... 5 more
I/ActivityManager(  913): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4883 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  913): Recipient 4863
I/ActivityManager(  913): Process com.google.android.apps.docs (pid 4863) has died.
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  913): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4896 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4883): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4883): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4883): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4883): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4883): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4883): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4883): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4883): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4883): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4883): threadid=10: thread exiting with uncaught exception (group=0x416fde30)
E/AndroidRuntime( 4883): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4883): Process: com.android.keychain, PID: 4883
E/AndroidRuntime( 4883): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4883): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4883): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4883): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4883): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4883): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4883): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4883): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  913): App crashed! Process: com.android.keychain
D/ErrorReport(  913): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4896): getInstance(Context context)
D/Process ( 4883): killProcess, pid=4883
D/Process ( 4883): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  913): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  913): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449064952780.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  913): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  913): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  913): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  913): 	... 4 more
D/AppTag  ( 4896): getInstance(Context context)
D/AppTag  ( 4896): onCreate()
I/ActivityManager(  913): Recipient 4883
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Process com.android.keychain (pid 4883) has died.
W/ActivityManager(  913): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  913): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1906): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1906): Clearing selected account for com.test.thalitest
D/PMS     (  913): acquireWL(4263e468): PARTIAL_WAKE_LOCK  AsyncService 0x1 3616 10160 null
D/PMS     (  913): releaseWL(4263e468): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  913): Resuming delayed broadcast
D/ChimeraCfgMgr( 1906): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1906): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1906): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1906): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1906): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  913): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 1906): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1906): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x652b53a0
E/SQLiteLog( 1906): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1906): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e3a16e0
W/dalvikvm( 1906): threadid=46: thread exiting with uncaught exception (group=0x416fde30)
E/SQLiteDatabase( 1906): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1906): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1906): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1906): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1906): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1906): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1906): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1906): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DriveAsyncService( 1906): disk I/O error (code 3850)
E/DriveAsyncService( 1906): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1906): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1906): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 1906): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1906): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1906): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 1906): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 1906): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1906): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1906): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1906): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1906): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1906): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1906): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1906): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1906): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 1906): Opened phenotype.db in read-only mode
E/SQLiteLog( 1906): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1906): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/google_analytics_v4.db, handle = 0x65a1c140
E/GAv4-SVC( 1906): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/GAv4-SVC( 1906): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1906): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 1906): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 1906): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1906): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1906): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1906): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1906): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1906): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1906): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
E/SQLiteOpenHelper( 1906): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1906): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1906): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1906): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1906): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1906): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1906): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1906): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1906): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1906): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1906): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1906): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1906): threadid=48: thread exiting with uncaught exception (group=0x416fde30)
W/PackageManager(  913): Unable to load service info ResolveInfo{4254dcd0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
W/BaseAppContext( 1906): Using Auth Proxy for data requests.
E/SQLiteLog( 1906): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1906): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/google_analytics_v4.db, handle = 0x65a1c140
E/GAv4-SVC( 1906): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1906): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/BaseAppContext( 1906): Using Auth Proxy for data requests.
E/AndroidRuntime( 1906): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1906): Process: com.google.android.gms, PID: 1906
E/AndroidRuntime( 1906): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1906): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1906): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1906): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1906): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1906): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1906): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1906): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1906): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1906): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1906): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1906): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1906): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3143)
E/AndroidRuntime( 1906): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1906): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:978)
E/AndroidRuntime( 1906): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1906): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1906): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1906): 	at java.lang.Thread.run(Thread.java:864)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1906/10029)
E/ActivityManager(  913): App crashed! Process: com.google.android.gms
E/SQLiteLog( 1906): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1906): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/google_analytics_v4.db, handle = 0x65a1c140
E/GAv4-SVC( 1906): Local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1906): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 1906): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/Process ( 1906): killProcess, pid=1906
E/DropBoxManagerService(  913): Can't write: system_app_crash
E/DropBoxManagerService(  913): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  913): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  913): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  913): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  913): 	... 5 more
D/Process ( 1906): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.d.uncaughtException:54 com.google.android.gms.analytics.f.uncaughtException:112 
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 1906
I/ActivityManager(  913): Process com.google.android.gms (pid 1906) has died.
D/PMS     (  913): handleWLDeath(43baf6f8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  913): Client connection lost with reason: 4
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.analytics.AnalyticsService in 1000ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20997ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20997ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20996ms
I/ActivityManager(  913): Resuming delayed broadcast
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20986ms
E/SQLiteLog( 1367): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1367): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x62a4e938
W/dalvikvm( 1367): threadid=1: thread exiting with uncaught exception (group=0x416fde30)
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41bc2d10 +
I/Prism.WidgetManager( 1278): onLoadItems() +
E/ActivityManager(  913): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1367): FATAL EXCEPTION: main
E/AndroidRuntime( 1367): Process: com.google.process.gapps, PID: 1367
E/AndroidRuntime( 1367): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1367): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1367): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1367): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1367): 	... 10 more
D/Process ( 1367): killProcess, pid=1367
D/Process ( 1367): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  913): Can't write: system_app_crash
E/DropBoxManagerService(  913): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  913): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  913): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  913): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  913): 	... 5 more
W/dalvikvm( 4047): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/ActivityManager(  913): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4927 uid=10098 gids={50098, 3003, 5012}
I/ActivityManager(  913): Recipient 1367
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  913): Client connection lost with reason: 4
I/ActivityManager(  913): Process com.google.process.gapps (pid 1367) has died.
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20858ms
I/DeviceManagement( 4927): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4927 dbg=false s=true
I/DeviceManagement( 4927): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4927): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4927): WorkflowService: Starting workflow service
I/DeviceManagement( 4927): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b5be58] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4927): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4927): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4927): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4927): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  913): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4941 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4927): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4927): SessionStateController: Checking invariants...

```
