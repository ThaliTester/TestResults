#### Test 549702613245198_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/SMSBackup( 4465): SMSBackupAgentService started
D/SMSBackup( 4465): Checking restore status
D/SMSBackup( 4465): Restore complete
D/SMSBackup( 4465): cancelCheckAlarm
,D/SMSBackup( 4465): SMSBackupAgentService completed: completed in 0.0 seconds
--------- beginning of /dev/log/system
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
D/Finsky  ( 4096): [431] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4096): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  909): killProcessQuiet, pid=4165
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4165:com.google.android.talk/u0a111 (adj 15): empty #17
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4165
E/cutils-trace( 4484): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4484): ====startRecUseTime====
D/htc.customization.log.level( 4484):  is 
W/CustomizationLogLevel( 4484): Level value is invalid, use default level 2
D/CustomizationManager( 4484):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4484): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4484): Parsing tag category name = system
I/CustomizationCIDLoader( 4484): Parsing tag category name = application
I/CustomizationCIDLoader( 4484): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4484): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4484): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4484): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4484): Parsing tag category name = Settings
D/CustomizationManager( 4484):  Read CID file spent 0.108 (s)
D/CustomizationManager( 4484):  All configurations done spent 0.109 (s)
W/HtcNativeFlag( 4484): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4484): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4484): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4484): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4484
D/PMS     (  909): acquireHCC(43bee478): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(439772d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
W/asset   (  909): Copying FileAsset 0x6932ece8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1140972760
D/PMS     (  909): acquireWL(4382db30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c6f260
I/SocialFeedProvider( 1275): +onPause
I/SocialFeedProvider( 1275): -onPause
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4495 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1275): [trimMemory] 20
W/asset   ( 4495): Copying FileAsset 0x5c811428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4495): Binding Chromium to main looper Looper (main, tid 1) {41ab9388}
I/LibraryLoader( 4495): Expected native library version number "",actual native library version number ""
I/chromium( 4495): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4495): Initializing chromium process, renderers=0
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  909): java.lang.Throwable: stack dump
D/PMS     (  909): acquireWL(43811b30): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  909): acquireWL(436ed178): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  909): releaseWL(43811b30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4259d940:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4495): 1101852096: getState(). Returning 12
I/Adreno-EGL( 4495): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4495): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4495): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4495): Local Branch: 
I/Adreno-EGL( 4495): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4495): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4495):                  aa63bbd948f41d15fc72f585e
W/chromium( 4495): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4495): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4495): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4495): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4495): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4495): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4495): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4495): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4495): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4495): CordovaWebView is running on device made by: HTC
,W/AwContents( 4495): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  909): Disable input method client, pid=1275
W/ResourceType( 4495): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4495): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b00470, mServedView=org.apache.cordova.engine.SystemWebView{41ac60d8 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  909): Enable input method client, pid=4495
W/AwContents( 4495): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +288ms
W/XT9_C   ( 1213): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1213): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  909): releaseWL(4382db30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4495): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4495): JniHelper::setJavaVM(0x41590048), pthread_self() = 1662353216
D/JX-Cordova( 4495): jxcore cordova android initializing
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 11.535MB for 63974-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 11.591MB for 95956-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 11.671MB for 143930-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 11.788MB for 215890-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 11.962MB for 323830-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 12.627MB for 728606-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 13.229MB for 1092904-byte allocation
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{440a9630 u0 com.htc.htclocationservice/.AutoSettingService}
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 14.132MB for 1639352-byte allocation
,V/LightsService(  909): setLight #0: color=#25
,V/LightsService(  909): setLight #0: color=#21
,V/LightsService(  909): setLight #0: color=#1b
,V/LightsService(  909): setLight #0: color=#14
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 15.456MB for 2459024-byte allocation
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(43bee478): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  909): releaseHCC(439772d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 6
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 12
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 17.583MB for 3688532-byte allocation
,W/jxcore-log( 4495): Initializing JXcore engine
,W/jxcore-log( 4495): JXcore engine is ready
,W/jxcore-log( 4495): Starting JXcore engine
,W/jxcore-log( 4495): Platform android
W/jxcore-log( 4495): 
,W/jxcore-log( 4495): Process ARCH arm
W/jxcore-log( 4495): 
,D/PMS     (  909): releaseWL(436ed178): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 4495): JXcore Cordova bridge is ready!
I/jxcore-log( 4495): 
,W/jxcore-log( 4495): JXcore engine is started
,I/chromium( 4495): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4495): Toggling radios to true
I/jxcore-log( 4495): 
,D/BluetoothAdapter( 4495): enable(): BT is already enabled..!
,D/WifiManager( 4495): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 2
,W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1104
,W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
,W/Settings:Agent(  909): 
,W/System.err(  909): java.lang.Throwable: stack dump
D/WifiService(  909): New client listening to asynchronous messages
D/WifiService(  909): setWifiEnabled: true pid=4495, uid=10389
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
W/Settings:Agent(  909): << traceCallingStack(): 6(ms)
D/WifiManager( 4495): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  909): doBoolean: DISCONNECT
D/WifiManager( 4495): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): TDLS: Tear down peers
I/wpa_supplicant( 1162): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4495): Radios toggled
I/jxcore-log( 4495): 
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1162): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1162): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1162): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12,
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8a9dbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
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
,D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
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
D/wpa_supplicant( 1162): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  909):    returned true
D/WifiPerfLock(  909): release()
,D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
,D/Tethering(  909): interfaceLinkStateChanged wlan0, false
,D/Tethering(  909): interfaceStatusChanged wlan0, false
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  909): acquireWL(4236ec00): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909): doBoolean: RECONNECT
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): Fast associate: Old scan results
I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  909):    returned true
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  909): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20492 mDataStallAlarmIntent=PendingIntent{432222b8: PendingIntentRecord{423d98a0 android broadcastIntent}}
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
D/DhcpStateMachine(  909): [RunningState] Stop DHCP
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
,D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  909): Exit handleNetworkDisconnect
D/WISPrService( 3829): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  909): isAvailable+-
D/UsbnetStateTracker(  909): reconnect
,D/UsbnetStateTracker(  909): isAvailable+-
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiService(  909): New client listening to asynchronous messages
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WISPrService( 3829): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3829): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3829): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,V/NativeCrypto( 1374): Read error: ssl=0x65fcc008: I/O error during system call, Connection timed out
,V/NativeCrypto( 1374): SSL shutdown failed: ssl=0x65fcc008: I/O error during system call, Broken pipe
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/ConnectivityService(  909): resetConnections(wlan0, 3)
D/PMS     (  909): acquireWL(42696318): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
D/libc    (  363): [NET] entry_id:3   entry:0xb765f108  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb765f2f0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb765f428  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb765efd8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb765f4f0  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb765af88  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
D/PMS     (  909): acquireWL(42565cd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1374/10029)
D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  909):    returned false
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:7
D/BatSI   (  909): WIFI scan started for: 650a0300 uid:1000
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  909): releaseWL(42696318): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/PMS     (  909): releaseWL(42565cd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
,I/SensorManager(  909): mEventCount = 900
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  909): ipv4Default null
I/Tethering(  909): No IPv4 upstream interface, giving up.
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  909): NoActiveNetworkState
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(42366758): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
D/PMS     (  909): releaseWL(42366758): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4369/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4296/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
,I/NetworkMonitor( 4369): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4296/10100)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2400/10021)
,I/ActivityManager(  909): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4547 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4547): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4547): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4547): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4547): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4547): Preparing secondary program dexes.
V/DexLibLoader( 4547): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4547): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4547): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4547): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4547): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4547): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4547): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4547): Dex already copied
D/OdexVerifier( 4547): Odex verification is skipped.
,V/DexLibLoader( 4547): Creating class loader
,V/DexLibLoader( 4547): Finished creating class loader
V/DexLibLoader( 4547): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4547): Dex already copied
D/OdexVerifier( 4547): Odex verification is skipped.
,V/DexLibLoader( 4547): Creating class loader,
V/DexLibLoader( 4547): Finished creating class loader,
V/DexLibLoader( 4547): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4547): Dex already copied
D/OdexVerifier( 4547): Odex verification is skipped.
,V/DexLibLoader( 4547): Creating class loader,
V/DexLibLoader( 4547): Finished creating class loader
V/DexLibLoader( 4547): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4547): Dex already copied
D/OdexVerifier( 4547): Odex verification is skipped.
,V/DexLibLoader( 4547): Creating class loader
,V/DexLibLoader( 4547): Finished creating class loader
,V/DexLibLoader( 4547): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4547): DexLibLoader.ensureDexLoaded took 20 ms,
,W/dalvikvm( 4547): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1162): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1162): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1162): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 3
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
D/wpa_supplicant( 1162): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8a9f4e8  current_ssid=0x0
D/wpa_supplicant( 1162): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1162): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1162): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1162): check if in concurrent case
,I/wpa_supplicant( 1162): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1162): RSN: PMKSA cache search - network_ctx=0xb8a9f4e8 try_opportunistic=0
D/wpa_supplicant( 1162): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1162): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1162): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1162): nl80211: Unsubscribe mgmt frames handle 0xb8a9e718 (mode change)
D/wpa_supplicant( 1162): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8a9e718
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a9e718
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a9e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a9e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a9e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a9e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a9e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a9e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a9e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a9e718
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a9e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1162):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162):   * freq=2412
D/wpa_supplicant( 1162):   * Auth Type 0
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
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
D/WirelessDisplayService(  909): getDiscoveryDongleList
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1162): reply (489) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000022430098
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-55
I/wpa_supplicant( 1162): tsf=0000000102261121
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=2
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000102261126
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-77
I/wpa_supplicant( 1162): tsf=0000000102261129
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ####
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 22430098, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 102261121, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 102261126, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 102261129, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
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
D/wpa_supplicant( 1162): Add randomness: count=11 entropy=4
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
,D/wpa_supplicant( 1162): Get randomness: len=32 entropy=5
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
,D/Tethering(  909): interfaceStatusChanged wlan0, false
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  909): Associated
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  909): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/Tethering(  909): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8a9e9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f39b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1162):    broadcast key
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1162): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1162): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1162): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
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
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1162): EAPOL authentication completed successfully
I/wpa_supplicant( 1162): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  909): interfaceStatusChanged wlan0, true
,D/Tethering(  909): [isWifi] getHotspotEnabled: false,
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false),
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WISPrService( 3829): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3829): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
,D/DhcpStateMachine(  909): [StoppedState] Start DHCP
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 1
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  909):    returned null
,E/FbInjectorInitializer( 4547): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/PMS     (  909): acquireWL(423365e0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4259cec8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4259cec8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4547): Verify
,D/WifiService(  909): New client listening to asynchronous messages
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4547): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4547): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  909): killProcessQuiet, pid=4265
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4265:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4265
,D/AutoSetting( 1317): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4574 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
,D/AutoSetting( 1317): Util - no network available!
,D/AutoSetting( 1317): service - onCreate()
,D/AutoSetting( 1317): service - AddressCache: using context: com.htc.Weather
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  909): request 4230d8f0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1317): service - mHandler: cancel location update
D/AutoSetting( 1317): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4574): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4574): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4574): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4574): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  909): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4590 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,W/fb4a(:<default>):UserScope( 4547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4547): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
,W/fb4a(:<default>):UserScope( 4547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4547): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  909): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4606 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=4296
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 4296:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,E/dalvikvm( 4547): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4547): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4547): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4547): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4547): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4547): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4547): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4547): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4547): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4547): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4547): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4547): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/dalvikvm( 4547): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4547): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4547): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4547): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4547): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4547): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4606): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4606): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4606): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4606): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4606): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 9.920MB for 39954-byte allocation
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 9.997MB for 79892-byte allocation
I/ActivityManager(  909): Recipient 4296
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 10.074MB for 84664-byte allocation
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4606/10151)
,V/WebViewChromiumFactoryProvider( 4606): Binding Chromium to main looper Looper (main, tid 1) {41abd170}
,I/LibraryLoader( 4606): Expected native library version number "",actual native library version number ""
,I/chromium( 4606): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4606): Initializing chromium process, renderers=0
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 10.093MB for 28144-byte allocation
,E/AudioManagerAndroid( 4606): BLUETOOTH permission is missing!
D/PMS     (  909): acquireWL(4395f410): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  909): acquireWL(43ed29f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  909): releaseWL(4395f410): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4606): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4606): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4606): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4606): Local Branch: 
I/Adreno-EGL( 4606): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4606): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4606):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4606): Starting up...
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4606/10151)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4606/10151)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4068/10160)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4068/10160)
,D/Process (  909): killProcessQuiet, pid=4312
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4312:com.htc.backup/1000 (adj 15): empty #17
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
,I/iu.Environment( 2150): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
I/ActivityManager(  909): Recipient 4312
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/iu.UploadsManager( 2150): num queued entries: 0
,I/iu.UploadsManager( 2150): num updated entries: 0
,I/iu.SyncManager( 2150): NEXT; no task
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43105fc8 u0 ReceiverList{43105ea8 4547 com.facebook.katana/10027/u0 remote:437ea1a8}}
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43105fc8 u0 ReceiverList{43105ea8 4547 com.facebook.katana/10027/u0 remote:437ea1a8}}
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42669ed8 u0 ReceiverList{42669e78 4547 com.facebook.katana/10027/u0 remote:4406d248}}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/PMS     (  909): acquireWL(439615a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(439615a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/wpa_supplicant( 1162): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1162): EAPOL: disable timer tick
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4547): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4547): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  909): releaseWL(423365e0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1162): Change stage from stage0 to stage3
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 96
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): gateway: /192.168.1.1
D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): WiFi gateway: 0x101a8c0
,I/wpa_supplicant( 1162): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20494 delay=15s
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WISPrService( 3829): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/WifiWatchdogStateMachine(  909): WAN detection
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@424408a0
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1118): WifiActivity: 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  909): acquireWL(42a59bb0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  909): acquireWL(434ea5a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2150 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2150): Checkin interval check for package: unspecified last checkin: 1452283643209 min interval config: 0 actual interval: 46501
D/PMS     (  909): acquireWL(432a1540): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2150 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(434ea5a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2150): Checking schedule, now: 1452283689716 next: 1452283672970
,I/CheckinService( 2150): active receiver: enabled
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2150, uid=10029, userID:0
,I/CheckinService( 2150): Preparing to send checkin request
,I/EventLogService( 2150): Accumulating logs since 1452283639038
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(42a59bb0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2150): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2150): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2150/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  909): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4681 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4681): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4681): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4681): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4681): install
,I/MultiDex( 4681): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4681): loading existing secondary dex files
,I/MultiDex( 4681): load found 3 secondary dex files
,I/MultiDex( 4681): install done
,W/dalvikvm( 4681): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4681): VFY: unable to resolve instance field 36
,W/dalvikvm( 4681): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4681): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4681): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1227): callingUid 10029, callindPid: 1227
,D/LocationInitializer( 2150): Restart initialization of location
,W/dalvikvm( 4681): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4681): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1374): Proximity feature is not enabled.
,E/MDM     ( 1227): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 4681): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4681): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4681): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4681): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4681): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,W/GCoreFlp( 1227): No location to return for getLastLocation()
,W/FusedLocationProvider( 1227): location=null
D/PMS     (  909): acquireWL(44119338): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(44119338): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/NativeLibraryUtils( 4681): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2024826239
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/Adreno-EGL( 4681): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4681): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4681): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4681): Local Branch: 
I/Adreno-EGL( 4681): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4681): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4681):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4681): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4681): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4681): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4681): Local Branch: 
I/Adreno-EGL( 4681): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4681): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4681):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  370): CdmEngine::OpenSession
I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=4265226403
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  909): releaseWL(4236ec00): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,I/WVCdm   (  370): CdmEngine::CloseSession
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
,V/Tethering(  909): bSetPropertyMultiRAB:false
,D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/CaptivePortalTracker(  909): NoActiveNetworkState
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
,I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  909): Found interface wlan0
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
I/NetworkMonitor( 4369): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/AccTypeManager( 1338): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4369/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
D/PMS     (  909): acquireWL(440643a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.musicenhancer (3945/10053)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2400/10021)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,W/AccTypeManager( 1338): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1338): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/AutoSetting( 1317): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/ExternalAccountType( 1338): Unsupported attribute readOnly
D/MobileConnectivityChangeReceiver( 4574): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4574): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4606/10151)
,D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1317): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1317): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1317): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1317): service - handleMessage() setting current location null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1317): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1317): service - onStartCommand() check timezone in 30000
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4068/10160)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4068/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(42825620): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): acquireWL(42a590d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2150 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
D/PMS     (  909): releaseWL(42825620): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  909): releaseWL(440643a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/CheckinService( 2150): Checkin interval check for package: unspecified last checkin: 1452283643209 min interval config: 0 actual interval: 47598
D/PMS     (  909): releaseWL(42a590d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/dalvikvm-heap( 4068): Grow heap (frag case) to 13.518MB for 1821008-byte allocation
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2150): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2150, uid=10029, userID:0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,I/iu.UploadsManager( 2150): num queued entries: 0
,I/iu.UploadsManager( 2150): num updated entries: 0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,I/iu.SyncManager( 2150): NEXT; no task
,D/libc    ( 1374): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/PMS     (  909): acquireWL(4236f408): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/libc    ( 1374): [NET] getaddrinfo-,err=8
D/libc    ( 1374): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1374): [NET] getaddrinfo-, 1
D/libc    ( 1374): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =349c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 252
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
W/Settings( 4681): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1374): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1374): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1374): [NET] getaddrinfo-,err=8
,D/libc    ( 1374): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1374): [NET] getaddrinfo-,err=8
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,I/Adreno-EGL( 4681): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4681): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4681): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4681): Local Branch: 
I/Adreno-EGL( 4681): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4681): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4681):                  aa63bbd948f41d15fc72f585e
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420b8668
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420b8668, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fd5690
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@42618f80
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  909): Going to sleep due to screen timeout...
I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,W/PMS     (  909): mWirelessDisplayManager is null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=28 [7][2][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 120
D/WifiStateMachine(  909): BroadcastRSSIForIMS, newrssi =-56 , oldRssi= -200
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4681/10029)
,D/PMS     (  909): acquireWL(431b54e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,D/PMS     (  909): releaseWL(4236f408): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1374/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/PMS     (  909): releaseWL(431b54e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4408fff8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1374/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1374/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/PMS     (  909): releaseWL(4408fff8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2150): Classify the device as Phone.
,D/libc    ( 2150): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2150): [NET] getaddrinfo-,err=8
D/libc    ( 2150): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2150): [NET] getaddrinfo-, 1
,D/libc    ( 2150): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ba10 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 311ms
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/PMS     (  909): OOBE c monitor 11
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4366d300)
D/NfcService( 1258): ScreenObserver: OFF
,D/NfcService( 1258): applyRouting - 0
,I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1258): applyRouting -2
D/PMN     (  909): wakingUp
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=4495
,D/PMS     (  909): acquireWL(440afc30): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 256
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2150): [NET] getaddrinfo_proxy-, success
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/WindowManager(  909): No lock screen! windowToken=null
D/PMS     (  909): acquireWL(43249928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(440afc30): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  909): onScreenOn
D/PMS     (  909): releaseWL(43249928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,D/libc    ( 2150): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2150): [NET] getaddrinfo-,err=8
,D/MtpService( 2400): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2400): [MTP][onReceive]-
,D/NfcService( 1258): applyRouting - 0
,D/AutoSetting( 1317): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1258): applyRouting -2
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/PMS     (  909): acquireWL(44134b60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  909): releaseWL(44134b60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
D/TetherSettings( 3829): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3829): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3829): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3829): Cust_ConnectToPC   : spcsc>false
D/        ( 3829): Cust_ConnectToPC   : IPT>true
D/        ( 3829): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3829): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3829): hasRemovableStorageSlot: true
D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20495 delay=15s
,D/SmartNS_Utility( 3829): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3829): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:On
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1162): BG scan when screen On
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): Match BG scan, scan!
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  909):    returned true
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,I/ClockThread( 1118): stop update clock
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,I/PSReceiver( 3829): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3829): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3829): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3829):  defaultType:0
,V/SRS_Proc(  370): ParamSet string: screen_state=on
D/WIFI_ICON( 1118): WifiActivity: 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/ContextImpl( 3829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  909): updateScreenOn: false
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4729 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  909): acquireWL(441140d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): releaseWL(441140d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(43343d80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4729): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  909): releaseWL(43343d80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1769): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1769): onScreenOn: 1452283691579
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1769): onScreenOn: 1452283691579
,D/SmartSyncUtils( 4729): isEpsOn(), nState = 0
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fd5690
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fd5690, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@42618f80
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  909): acquireWL(43353870): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4729 1000 null
D/PMN     (  909): goingToSleep
,D/PMS     (  909): acquireWL(440dd258): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43353870): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20495 mDataStallAlarmIntent=PendingIntent{4381a860: PendingIntentRecord{423d98a0 android broadcastIntent}}
I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
D/PMS     (  909): acquireWL(433532a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/SmartSyncUtils( 4729): getMobilePolicyEnabled, result = true
,D/Process (  909): killProcessQuiet, pid=4283
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4283:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4283
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 4547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/PMS     (  909): releaseWL(43ed29f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4547): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4547/10027)
,W/ActivityManager(  909): Activity pause timeout for ActivityRecord{424570c8 u0 com.test.thalitest/.MainActivity t2}
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:Off
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1162): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 144
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  909): updateScreenOn: false
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
W/ContextImpl( 4729): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4729): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4729): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4729): isEpsOn(), nState = 0
D/WifiService(  909): New client listening to asynchronous messages
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42618f80
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42618f80, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42618f80, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42618f80
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42649270 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42649270 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  909): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  909): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  909): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  909): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  909): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  909): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  909): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  909): acquireWL(428dc710): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] getTotalRam: 1873 Mb
D/PMS     (  909): releaseWL(428dc710): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(4382a0c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1769): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1769): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1769): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1769): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1769): onScreenOff
D/PMS     (  909): releaseWL(4382a0c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1317): service - mHandler: cancel location update
,D/AutoSetting( 1317): service -           changes count: 0
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7f77 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  909): releaseWL(433532a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=12 entropy=0
D/wpa_supplicant( 1162): Add randomness: count=13 entropy=1
D/wpa_supplicant( 1162): Add randomness: count=14 entropy=2
D/wpa_supplicant( 1162): Add randomness: count=15 entropy=3
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1162): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/w,pa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=16 entropy=4
D/wpa_supplicant( 1162): Add randomness: count=17 entropy=5
D/wpa_supplicant( 1162): Add randomness: count=18 entropy=6
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1162): Add randomness: count=19 entropy=7
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1162): reply (489) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000022430098
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000107914278
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=2
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000107914268
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-77
I/wpa_supplicant( 1162): tsf=0000000107914287
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ####
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4408e280 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4408e280 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4408e280 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 22430098, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 107914278, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 107914268, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 107914287, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiManager( 1227): getScanResults enter 
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/104.81.130.175
,I/GAV2    ( 4606): Thread[GAThread,5,main]: No campaign data found.
,D/libc    ( 2150): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2150): [NET] getaddrinfo-,err=8
D/libc    ( 2150): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2150): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2150): Sending checkin request (12210 bytes)
,I/CheckinRequestBuilder( 2150): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2150): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2150/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=16 [30][5][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
,I/CheckinRequestBuilder( 2150): Classify the device as Phone.
,I/CheckinTask( 2150): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2150): Checking schedule, now: 1452283694382 next: 1452806631375
,I/CheckinService( 2150): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2150, uid=10029, userID:0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
,I/jxcore-log( 4495): Test app app.js loaded
I/jxcore-log( 4495): 
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
I/Choreographer( 4495): Skipped 526 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4495): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4495): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41ac60d8 VFEDH.C. .F....ID 0,0-720,1134 #64}
I/CheckinService( 2150): Checking schedule, now: 1452283694421 next: 1452806631375
,I/CheckinService( 2150): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2150, uid=10029, userID:0
,D/CheckinService( 2150): Recording last checkin time for package unspecified as 1452283694426
,I/chromium( 4495): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  909): releaseWL(440dd258): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
D/PMS     (  909): releaseWL(432a1540): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2150/10029)
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Process (  909): killProcessQuiet, pid=4335
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4335:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4335
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1516): service - handleMessage() stop self
,D/AutoSetting( 1516): service - onDestroy() END
,D/AutoSetting( 1516): service - handleMessage() quit looper
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1338): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  909): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4760 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1275): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1338): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1338): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  909):   Scheme: "smsto"
I/Launcher( 1275): Deferring update until onResume
,D/Launcher( 1275): waitUntilResume // bindAppsUpdated
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1338): Unsupported attribute readOnly
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4760): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4760): MmsConfig.loadMmsSettings
,W/dalvikvm( 4760): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4760): VFY: unable to resolve instance field 36
,W/dalvikvm( 4760): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4760): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  909): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4783 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4760, uid=10111, userID:0
,W/Settings( 4760): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4783): onCreate
,V/GetPrviateResource( 4783): GetPrviateResource
,V/GetPrviateResource( 4783): GetPrviateResource
,D/MmsCustomizationProvider( 4783): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4760, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4760, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4760, uid=10111, userID:0
,D/MmsCustomizationProvider( 4783): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4760): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4760): MmsConfig.loadFromDatabase
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4760, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4760, uid=10111, userID:0
D/PMS     (  909): acquireWL(440b2068): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4760 10111 null
,E/Babel   ( 4760): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4760): MmsConfig.loadFromResources
,E/Babel   ( 4760): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4760): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ProviderInstaller( 4760): Installed default security provider GmsCore_OpenSSL
I/[PluginManager]RegisterService( 1317): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1317): handle notify Blinkfeed plugin client changed
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 4389:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4389
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  909): Recipient 4389
,D/WifiService(  909): Client connection lost with reason: 4
,I/IcingCorporaProvider( 2856): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MessageCustFlag( 4783): sense_version=6.0
,D/BTAccessoryUtil( 4783): createReceiver
D/PMS     (  909): releaseWL(440b2068): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/BTAccessoryUtil( 4783): registerReceiver return intent = null
D/MessageCustFlag( 4783): sku_id=99
,W/SystemReader( 4783): Cannot find message_ambs_application_id, use default value instead
,D/Process (  909): killProcessQuiet, pid=3867
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(43c5be58): PARTIAL_WAKE_LOCK  Icing 0x1 2150 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Killing 3867:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Messaging( 4783): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4783): networkCode: 
D/MessageCustFlag( 4783): sku_id=99
D/MmsConfig( 4783): SIE smsPri: null
D/MmsConfig( 4783): networkCode: 
D/HtcTelephonyCapability( 4783): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4783): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4783): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4783): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,W/PackageManager(  909): Unable to load service info ResolveInfo{4318c330 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  909): Recipient 3867
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): releaseWL(43c5be58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(41ad9b80): PARTIAL_WAKE_LOCK  Icing 0x1 2150 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 15.218MB for 1821008-byte allocation
D/PMS     (  909): acquireWL(41e57350): PARTIAL_WAKE_LOCK  AsyncService 0x1 4068 10160 null
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.950MB for 1821008-byte allocation,
D/PMS     (  909): releaseWL(41ad9b80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(41e57350): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  909): acquireWL(4318cfb8): PARTIAL_WAKE_LOCK  Icing 0x1 2150 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4318cfb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  909): acquireWL(430f9390): PARTIAL_WAKE_LOCK  Icing 0x1 2150 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(430f9390): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  909): acquireWL(423df230): PARTIAL_WAKE_LOCK  Icing 0x1 2150 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(423df230): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2150): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/PMS     (  909): acquireWL(42338a98): PARTIAL_WAKE_LOCK  Icing 0x1 2150 10029 WorkSource{10029 com.google.android.gms}
,I/PackageBroadcastService( 2150): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2150): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,I/GCoreNlp( 1227): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  909): applying state to connected service
D/PMS     (  909): acquireWL(44129998): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(44129998): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  909): applying state to connected service
,D/PMS     (  909): acquireWL(421aecd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2856): UpdateCorporaTask done [took 372 ms] updated apps [took 372 ms] 
D/PMS     (  909): releaseWL(421aecd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(43565928): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43565928): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b4bc10 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,I/Icing   ( 2150): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2150): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
E/Prism.WidgetManager( 1275): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1275): onLoadItems() -
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b4bc10 -
D/PMS     (  909): releaseWL(42338a98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1243): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1243): -- N1 =0
,D/PhoneApp( 1243): -- N2 =0
,D/PhoneApp( 1243): -- N3 =0
,D/Messaging( 4783): mNeedToUpdateDate2 start
,D/MmsConfig( 4783): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4783): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4783): 
D/MmsAsyncWorkHandler( 4783): HM tk = 20001
,D/ReportIndicatorCache( 4783): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4783): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41abf5a0
,I/Messaging( 4783): mccmnc> 
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/DraftCache( 4783): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4783): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4783): networkCode: 
,D/Messaging( 4783): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1243): sku_id=99
D/PhoneStorageUtil( 4783): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4783): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4783): createReceiver
,D/MessageCustFlag( 4783): sense_version=6.0
,D/Jerry   ( 4783): start to preload cursor >>>>>>>
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1243):  phoneType = -1
D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4783): [DraftCache/478] rebuildCache
,D/TelephUtils( 1243): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
V/MmsProvider( 1243): Update uri=content://mms, match=0
D/Messaging( 4783): mNeedToUpdateDate2: false
,V/MmsProvider( 1243): selection=st=129 AND m_type!=134
,D/Messaging( 4783): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4783): TransactionService is going to be woken up.
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,V/TransactionService( 4783): 1-Creating TransactionService
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,V/TransactionService( 4783): onStartCommand: 1
,D/MmsSystemEventReceiver( 4783): unRegisterForConnectionStateChanges
V/TransactionService( 4783): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4783): Loading previous transactions.
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/Jerry   ( 1243): URI_DRAFT
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1243): device_type: 1
D/DraftCache( 4783): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4783): [DraftCache/478] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4783): 
D/MmsAsyncWorkHandler( 4783): HM tk = 20002
D/Messaging( 4783): ViewCache CreatePreload
,D/Messaging( 4783): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1243):  phoneType = -1
D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TransactionService( 4783): Force set service start id to 1
V/TransactionService( 4783): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4783): unRegisterForConnectionStateChanges
D/TransactionService( 4783): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4783): Destroying TransactionService
,D/Cust_MMSMS( 4783): _has_set_default_values_2=true
,V/TransactionService( 4783): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1243): sku_id=99
,D/Messaging( 4783): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MsgPreferenceUtils( 4783): def_index: 0
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MsgPreferenceUtils( 4783): globalIndex = 1
,D/AccFlag ( 1243): sku_id=99
D/MsgPreferenceUtils( 4783): phone state: true,
D/MsgPreferenceUtils( 4783): sd state: false
,D/MsgPreferenceUtils( 4783): vIndex = 0
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{425da350 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/Process (  909): killProcessQuiet, pid=3945
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3945:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3945
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV4    ( 4760): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=20 entropy=8
D/wpa_supplicant( 1162): Add randomness: count=21 entropy=9
D/wpa_supplicant( 1162): Add randomness: count=22 entropy=10
D/wpa_supplicant( 1162): Add randomness: count=23 entropy=11
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1162): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
,D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=24 entropy=12
D/wpa_supplicant( 1162): Add randomness: count=25 entropy=13
D/wpa_supplicant( 1162): Add randomness: count=26 entropy=14
,D/wpa_supplicant( 1162): Add randomness: count=27 entropy=15
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1162): reply (489) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000125043971
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000125044008
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=2
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000125043998
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-77
I/wpa_supplicant( 1162): tsf=0000000125044019
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 125043971, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 125044008, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 125043998, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 125044019, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(426b7fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  909): releaseWL(426b7fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1317): service - mHandler: update timezone
,D/AutoSetting( 1516): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1516): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1516): service - onCreate()
,W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1516): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1516): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1564): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1516): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1516): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1516): service - mHandler: update timezone
,D/AutoSetting( 1516): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1516): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1516): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1516): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41d634d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 11 2 11
,D/PMS     (  909): acquireWL(44114890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{426e0e78: PendingIntentRecord{42a5a3a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=125601, Int=0
,D/AutoSetting( 1317): service - handleMessage() stop self
V/AlarmManager(  909): sending alarm PendingIntent{41b2dac8: PendingIntentRecord{42baa598 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136738, Int=0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(42622898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
,D/AutoSetting( 1317): service - handleMessage() quit looper
,D/AutoSetting( 1317): service - onDestroy() END
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=6 [15][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(429b31b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(429b31b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42622898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(44114890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43b5a9a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/PMS     (  909): releaseWL(43b5a9a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4265e3c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/PMS     (  909): acquireWL(42a6f6b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(425d3028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1227): Vacuum at: now=1452283722581 tag=VacuumService
D/PMS     (  909): releaseWL(4265e3c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42a6f6b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43c8aa10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/PMS     (  909): releaseWL(43c8aa10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4296a390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/PMS     (  909): releaseWL(4296a390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(434bd038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(425d3028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/PMS     (  909): acquireWL(42bcabf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(434bd038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43189798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42bcabf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/PMS     (  909): releaseWL(43189798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43466740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/PMS     (  909): releaseWL(43466740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43516590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1374/10029)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/PMS     (  909): releaseWL(43516590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(4260b508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42503658: PendingIntentRecord{4259f6a0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142119, Int=0
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1162): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=28 entropy=16
D/wpa_supplicant( 1162): Add randomness: count=29 entropy=17
D/wpa_supplicant( 1162): Add randomness: count=30 entropy=18
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1162): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=31 entropy=19
D/wpa_supplicant( 1162): Add randomness: count=32 entropy=20
D/wpa_supplicant( 1162): Add randomness: count=33 entropy=21
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1162): reply (489) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000142152318
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000142152344
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=2
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000125043998
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-78
I/wpa_supplicant( 1162): tsf=0000000142152355
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 142152318, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  909): InactiveState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 142152344, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  909): P2pEnabledState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 125043998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 142152355, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  909): DefaultState{ when=-20ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(429bf460): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(4260b508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a2a4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  909): killProcessQuiet, pid=4419
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4419:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4419
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  909): releaseWL(429bf460): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{426a3a90 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  909): acquireWL(431eef08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{420306a8: PendingIntentRecord{42025020 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=154436, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(431eef08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=34 entropy=22
D/wpa_supplicant( 1162): Add randomness: count=35 entropy=23
D/wpa_supplicant( 1162): Add randomness: count=36 entropy=24
D/wpa_supplicant( 1162): Add randomness: count=37 entropy=25
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1162): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL], c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=38 entropy=26
D/wpa_supplicant( 1162): Add randomness: count=39 entropy=27
D/wpa_supplicant( 1162): Add randomness: count=40 entropy=28
D/wpa_supplicant( 1162): Add randomness: count=41 entropy=29
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1162): reply (523) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000159383628
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000159383653
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-78
I/wpa_supplicant( 1162): tsf=0000000159383664
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-92
I/wpa_supplicant( 1162): tsf=0000000159383673
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC4688432
I/wpa_supplicant( 1162): ####
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 159383628, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 159383653, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 159383664, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 159383673, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-12ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  909): getDiscoveryDongleList
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiManager( 1227): getScanResults enter 
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/AutoSetting( 1516): service - handleMessage() stop self
,D/AutoSetting( 1516): service - onDestroy() END
,D/AutoSetting( 1516): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4434
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4434:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4434
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(437ac2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(437ac2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=42 entropy=30
D/wpa_supplicant( 1162): Add randomness: count=43 entropy=31
D/wpa_supplicant( 1162): Add randomness: count=44 entropy=32
D/wpa_supplicant( 1162): Add randomness: count=45 entropy=33
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1162): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=46 entropy=34
D/wpa_supplicant( 1162): Add randomness: count=47 entropy=35
,D/wpa_supplicant( 1162): Add randomness: count=48 entropy=36
D/wpa_supplicant( 1162): Add randomness: count=49 entropy=37
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1,
I/wpa_supplicant( 1162): reply (523) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000176693752
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
,I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000176693780
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-78
I/wpa_supplicant( 1162): tsf=0000000176693793
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-92
I/wpa_supplicant( 1162): tsf=0000000176693802
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC4688432
I/wpa_supplicant( 1162): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 176693752, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 176693780, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 176693793, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 176693802, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(425ddc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(425ddc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=50 entropy=38
D/wpa_supplicant( 1162): Add randomness: count=51 entropy=39
D/wpa_supplicant( 1162): Add randomness: count=52 entropy=40
D/wpa_supplicant( 1162): Add randomness: count=53 entropy=41
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1162): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
,I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32,
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=54 entropy=42
D/wpa_supplicant( 1162): Add randomness: count=55 entropy=43
D/wpa_supplicant( 1162): Add randomness: count=56 entropy=44
D/wpa_supplicant( 1162): Add randomness: count=57 entropy=45
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1162): reply (523) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000194003356
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssi,d=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000194003383
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-78
I/wpa_supplicant( 1162): tsf=0000000194003394
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-92
I/wpa_supplicant( 1162): tsf=0000000194003404
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC4688432
I/wpa_supplicant( 1162): ####
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 194003356, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 194003383, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 194003394, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 194003404, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,D/WifiP2pService(  909): DefaultState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000),
D/WirelessDisplayService(  909): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=58 entropy=46
D/wpa_supplicant( 1162): Add randomness: count=59 entropy=47
D/wpa_supplicant( 1162): Add randomness: count=60 entropy=48
D/wpa_supplicant( 1162): Add randomness: count=61 entropy=49
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1162): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): ,[NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=62 entropy=50
D/wpa_supplicant( 1162): Add randomness: count=63 entropy=51
D/wpa_supplicant( 1162): Add randomness: count=64 entropy=52
D/wpa_supplicant( 1162): Add randomness: count=65 entropy=53
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1162): reply (523) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000211383818
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000211383847
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-78
I/wpa_supplicant( 1162): tsf=0000000211383859
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-91
I/wpa_supplicant( 1162): tsf=0000000211383868
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC4688432
I/wpa_supplicant( 1162): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 211383818, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 211383847, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 211383859, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 211383868, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000),
,D/PMS     (  909): acquireWL(4318ca38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{420306a8: PendingIntentRecord{42025020 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=214436, Int=0
I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4318ca38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42a1a860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10027}
,V/AlarmManager(  909): sending alarm PendingIntent{42662be8: PendingIntentRecord{4395ba20 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=223293, Int=0
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4856 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{421678d0: PendingIntentRecord{42658548 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452283797169, Int=10800000
,D/PMS     (  909): releaseWL(42a1a860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4856/10049)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024193
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024742
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024749
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024752
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026140
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026152
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028744
,D/Process (  909): killProcessQuiet, pid=4140
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4140:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4140
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(42bf9bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10027}
,V/AlarmManager(  909): sending alarm PendingIntent{423f7608: PendingIntentRecord{4395ba20 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226044, Int=0
,D/PMS     (  909): releaseWL(42bf9bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  909): acquireWL(4269dc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(4269dc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
,D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56,
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=66 entropy=54
D/wpa_supplicant( 1162): Add randomness: count=67 entropy=55
D/wpa_supplicant( 1162): Add randomness: count=68 entropy=56
D/wpa_supplicant( 1162): Add randomness: count=69 entropy=57
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1162): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
,I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=70 entropy=58
D/wpa_supplicant( 1162): Add randomness: count=71 entropy=59
D/wpa_supplicant( 1162): Add randomness: count=72 entropy=60
D/wpa_supplicant( 1162): Add randomness: count=73 entropy=61
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1162): reply (523) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000211383818
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000228522531
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-78
I/wpa_supplicant( 1162): tsf=0000000228522543
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-90
I/wpa_supplicant( 1162): tsf=0000000228522552
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC4688432
,I/wpa_supplicant( 1162): ####
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 211383818, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  909): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 228522531, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 228522543, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 228522552, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): == (4) end of scan result ==
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=74 entropy=62
D/wpa_supplicant( 1162): Add randomness: count=75 entropy=63
D/wpa_supplicant( 1162): Add randomness: count=76 entropy=64
D/wpa_supplicant( 1162): Add randomness: count=77 entropy=65
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1162): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): ,[NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=78 entropy=66
D/wpa_supplicant( 1162): Add randomness: count=79 entropy=67
D/wpa_supplicant( 1162): Add randomness: count=80 entropy=68
D/wpa_supplicant( 1162): Add randomness: count=81 entropy=69
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1162): reply (523) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000245813918
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000245813945
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-78
I/wpa_supplicant( 1162): tsf=0000000245813956
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-90
I/wpa_supplicant( 1162): tsf=0000000245813965
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC4688432
I/wpa_supplicant( 1162): ####
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 245813918, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 245813945, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 245813956, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 245813965, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiManager( 1227): getScanResults enter 
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/PMS     (  909): acquireWL(43b4e608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): releaseWL(43b4e608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1162): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=82 entropy=70
D/wpa_supplicant( 1162): Add randomness: count=83 entropy=71
D/wpa_supplicant( 1162): Add randomness: count=84 entropy=72
D/wpa_supplicant( 1162): Add randomness: count=85 entropy=73
D/wpa_supplicant( 1162): Add randomness: count=86 entropy=74
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1162): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1162): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): ,send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1162): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=87 entropy=75
D/wpa_supplicant( 1162): Add randomness: count=88 entropy=76
D/wpa_supplicant( 1162): Add randomness: count=89 entropy=77
D/wpa_supplicant( 1162): Add randomness: count=90 entropy=78
D/wpa_supplicant( 1162): Add randomness: count=91 entropy=79
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1162): reply (636) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000263063899
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000263063937
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-77
I/wpa_supplicant( 1162): tsf=0000000263063948
I/wpa_su,pplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-90
I/wpa_supplicant( 1162): tsf=0000000263063956
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC4688432
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=5
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000263063925
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 263063899, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 263063937, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 263063948, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 263063956, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 263063925, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList,
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(430fa9f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{420306a8: PendingIntentRecord{42025020 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=274436, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(430fa9f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=92 entropy=80
D/wpa_supplicant( 1162): Add randomness: count=93 entropy=81
D/wpa_supplicant( 1162): Add randomness: count=94 entropy=82
D/wpa_supplicant( 1162): Add randomness: count=95 entropy=83
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1162): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1162): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant(, 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=96 entropy=84
D/wpa_supplicant( 1162): Add randomness: count=97 entropy=85
D/wpa_supplicant( 1162): Add randomness: count=98 entropy=86
D/wpa_supplicant( 1162): Add randomness: count=99 entropy=87
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1162): reply (636) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000280202438
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000280202476
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-77
I/wpa_supplicant( 1162): tsf=0000000280202486
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-90
I/wpa_supplicant( 1162): tsf=0000000263063956
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC4688432
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=5
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000280202464
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ####
,D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 280202438, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 280202476, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 280202486, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 263063956, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 280202464, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43c72920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43c72920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=100 entropy=88
D/wpa_supplicant( 1162): Add randomness: count=101 entropy=89
D/wpa_supplicant( 1162): Add randomness: count=102 entropy=90
D/wpa_supplicant( 1162): Add randomness: count=103 entropy=91
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 9
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1162): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1162): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1162): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
,I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=104 entropy=92
D/wpa_supplicant( 1162): Add randomness: count=105 entropy=93
D/wpa_supplicant( 1162): Add randomness: count=106 entropy=94
D/wpa_supplicant( 1162): Add randomness: count=107 entropy=95
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): clear disabled list - type=1
I/wpa_supplicant( 1162): No suitable network found
W/wpa_supplicant( 1162): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1162): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1162): reply (489) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-48
I/wpa_supplicant( 1162): tsf=0000000297524061
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====,
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000297524099
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-77
I/wpa_supplicant( 1162): tsf=0000000297524109
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=5
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000297524088
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 297524061, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 297524099, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 297524109, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 297524088, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiManager( 1227): getScanResults enter 
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/jxcore-log( 4495): --= Surplus to requirements =--
I/jxcore-log( 4495): 
I/jxcore-log( 4495): ****TEST TOOK:  ms ****
I/jxcore-log( 4495): 
,I/jxcore-log( 4495): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4495): 
,E/cutils-trace( 4880): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4880): ====startRecUseTime====
D/htc.customization.log.level( 4880):  is 
,W/CustomizationLogLevel( 4880): Level value is invalid, use default level 2
,D/CustomizationManager( 4880):  Read ACC file spent 0.102 (s)
D/CIDMapFileReader( 4880): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4880): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4880): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4880): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4880): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4880): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4880): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4880): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4880): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4880): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4880): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4880): Parsing tag category name = system
,I/CustomizationCIDLoader( 4880): Parsing tag category name = application
I/CustomizationCIDLoader( 4880): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4880): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4880): Parsing tag category name = AudioService,
I/CustomizationCIDLoader( 4880): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 4880): Parsing tag category name = Settings
D/CustomizationManager( 4880):  Read CID file spent 0.153 (s)
,D/CustomizationManager( 4880):  All configurations done spent 0.153 (s)
,W/HtcNativeFlag( 4880): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4880): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4880): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4880): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4880, uid=2000 user=0
,I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  909): killProcessQuiet, pid=4495
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  909): Killing 4495:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
,W/ActivityManager(  909): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  909):   Force finishing activity ActivityRecord{424570c8 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  909): Copying FileAsset 0x684e5d18 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  909): channel '424622a0 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  909): channel '424622a0 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  909): Attempted to unregister already unregistered input channel '424622a0 com.test.thalitest.MainActivity (s)'
I/WindowState(  909): WIN DEATH: Window{424622a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  909): Client connection lost with reason: 4
,I/WindowManager(  909): WINDOW DIED Window{424622a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 4495 uid 10389
,W/Binder  ( 1213): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1213): java.lang.NullPointerException
W/Binder  ( 1213): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1213): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1213): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1213): 	at dalvik.system.NativeStart.run(Native Method)
W/PackageSettings(  909): Skipping PackageSetting{4224ab10 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1564): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1564): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/GeofencerStateMachine( 1227): Ignoring removeGeofence because network location is disabled.
D/PMS     (  909): acquireWL(4418f8c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/AccTypeManager( 1338): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): releaseWL(4418f8c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/Launcher( 1275): Deferring update until onResume
D/Launcher( 1275): waitUntilResume // bindAppsRemoved
,W/AccTypeManager( 1338): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1338): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,D/VoicemailCleanupService( 1288): Cleaning up data for package: com.test.thalitest
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/[PluginManager]RegisterService( 1317): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/[PluginManager]RegisterService( 1317): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1338): Unsupported attribute readOnly
,I/IcingCorporaProvider( 2856): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4895 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  909): acquireWL(41acdfa8): PARTIAL_WAKE_LOCK  Icing 0x1 2150 10029 WorkSource{10029 com.google.android.gms}
,E/Icing   ( 2150): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,E/Icing   ( 2150): Writing status failed
,E/Icing   ( 2150): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SQLiteLog( 2856): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2856): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x617b7080
,E/IcingCorporaProvider( 2856): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2856): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2856): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2856): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2856): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2856): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2856): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2856): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2856): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2856): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2856): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2856): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2856): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2856): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2856): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2856): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2856): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2856): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2856): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2856): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2856): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2856): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2856): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2856): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2856): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2856): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2856): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2856): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2856): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2856): 	... 15 more
W/IcingCorporaProvider( 2856): notifyTableChanged failed.
W/IcingCorporaProvider( 2856): Table change notification failed for TableStorageSpec[applications]
,I/IcingCorporaProvider( 2856): UpdateCorporaTask done [took 312 ms] updated apps [took 312 ms] 
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/PMS     (  909): releaseWL(41acdfa8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/SQLiteDatabase( 4895): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4895): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4895): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4895): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4895): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4895): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4895): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4895): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4895): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4895): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4895): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4895): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4895): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4895): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4895): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4895): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4895): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4895): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4895): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4895): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4895): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4895): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4895): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4895): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4895): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4895): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4895): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4895): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4895): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4895): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4895): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4895): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4895): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4895): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4895): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4895): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4895): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4895): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4895): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4895): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4895): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4895): threadid=11: thread exiting with uncaught exception (group=0x41688e30)
,E/AndroidRuntime( 4895): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4895): Process: com.google.android.apps.docs, PID: 4895
E/AndroidRuntime( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4895): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4895): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4895): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4895): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4895): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
,E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
,I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4913 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/SQLiteDatabase( 4895): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4895): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4895): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4895): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4895): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4895): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4895): 	at dalvik.system.NativeStart.main(Native Method)
,D/Process ( 4895): killProcess, pid=4895
D/Process ( 4895): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/SQLiteOpenHelper( 4895): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4895): 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4895): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4895): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4895): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4895): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4895): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4895): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  909): Recipient 4895
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  909): killProcessQuiet, pid=4465
,I/ActivityManager(  909): Killing 4465:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Process com.google.android.apps.docs (pid 4895) has died.
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4465
,W/ContextImpl( 4913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4913): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
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
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4913): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4913): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4913): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4913): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4913): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4913): threadid=10: thread exiting with uncaught exception (group=0x41688e30)
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4926 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/AndroidRuntime( 4913): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4913): Process: com.android.keychain, PID: 4913
E/AndroidRuntime( 4913): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4913): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4913): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4913): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4913): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4913): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4913): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4913): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  909): App crashed! Process: com.android.keychain
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4913): killProcess, pid=4913
,D/AppTag  ( 4926): getInstance(Context context)
,D/Process ( 4913): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452283890877.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
,I/ActivityManager(  909): Recipient 4913
,I/ActivityManager(  909): Process com.android.keychain (pid 4913) has died.
,W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms,
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AppTag  ( 4926): getInstance(Context context)
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b4bc10 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,D/AppTag  ( 4926): onCreate()
,D/PMS     (  909): acquireWL(4261c968): PARTIAL_WAKE_LOCK  AsyncService 0x1 4068 10160 null
,D/PMS     (  909): releaseWL(4261c968): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4096): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/PackageBroadcastService( 2150): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2150): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2150): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2150): Module APK com.google.android.play.games already loaded
,W/PackageManager(  909): Unable to load service info ResolveInfo{43ca3380 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
D/ChimeraCfgMgr( 2150): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2150): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 2150): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2150): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e3e56f8
,W/dalvikvm( 2150): threadid=44: thread exiting with uncaught exception (group=0x41688e30)
,E/SQLiteLog( 1374): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1374): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5cc69cf0
E/SQLiteLog( 2150): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1374): threadid=1: thread exiting with uncaught exception (group=0x41688e30)
,E/SQLiteDBG( 2150): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6535c790
I/ActivityManager(  909): Delay finish: com.google.android.gms/.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,E/AndroidRuntime( 2150): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2150): Process: com.google.android.gms, PID: 2150
E/AndroidRuntime( 2150): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2150): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2150): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2150): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2150): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2150): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2150): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2150): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2150): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2150): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2150): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2150): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2150): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2150): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2150): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2150): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2150): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2150): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2150): 	at java.lang.Thread.run(Thread.java:864)
E/DriveAsyncService( 2150): disk I/O error (code 3850)
E/DriveAsyncService( 2150): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2150): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2150): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2150): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2150): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2150): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2150): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2150): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2150): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2150): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2150): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2150): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2150): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2150): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2150): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2150): 	at java.lang.Thread.run(Thread.java:864)
,E/ActivityManager(  909): App crashed! Process: com.google.android.gms
,I/LocationSettingsChecker( 2150): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager(  909): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1374): FATAL EXCEPTION: main
E/AndroidRuntime( 1374): Process: com.google.process.gapps, PID: 1374
E/AndroidRuntime( 1374): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1374): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1374): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1374): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1374): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1374): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1374): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1374): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1374): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1374): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1374): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1374): 	... 10 more
,E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
D/Process ( 2150): killProcess, pid=2150
,D/Process ( 2150): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,D/Process ( 1374): killProcess, pid=1374
,D/Process ( 1374): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
,I/ActivityManager(  909): Recipient 1374
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
I/ActivityManager(  909): Recipient 2150
I/ActivityManager(  909): Process com.google.android.gms (pid 2150) has died.
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,I/ActivityManager(  909): Resuming delayed broadcast
,W/BroadcastQueue(  909): Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.gcm.nts.SchedulerReceiver}
W/BroadcastQueue(  909): android.os.DeadObjectException
W/BroadcastQueue(  909): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  909): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  909): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  909): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  909): 	at com.android.server.am.BroadcastQueue.backgroundServicesFinishedLocked(BroadcastQueue.java:442)
W/BroadcastQueue(  909): 	at com.android.server.am.ActivityManagerService.backgroundServicesFinishedLocked(ActivityManagerService.java:15042)
W/BroadcastQueue(  909): 	at com.android.server.am.ActiveServices$ServiceMap.rescheduleDelayedStarts(ActiveServices.java:237)
W/BroadcastQueue(  909): 	at com.android.server.am.ActiveServices$ServiceMap.ensureNotStartingBackground(ActiveServices.java:191)
W/BroadcastQueue(  909): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1711)
W/BroadcastQueue(  909): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2185)
W/BroadcastQueue(  909): 	,at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:13536)
W/BroadcastQueue(  909): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:3943)
W/BroadcastQueue(  909): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4128)
W/BroadcastQueue(  909): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
W/BroadcastQueue(  909): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/BroadcastQueue(  909): 	at dalvik.system.NativeStart.run(Native Method)
,W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,I/ActivityManager(  909): Start proc com.google.process.gapps for broadcast com.google.android.gms/.gcm.nts.SchedulerReceiver: pid=4957 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10982ms
,W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20981ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20981ms
,W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30981ms
,I/ActivityManager(  909): Process com.google.process.gapps (pid 1374) has died and restarted (pid 4957).

```
