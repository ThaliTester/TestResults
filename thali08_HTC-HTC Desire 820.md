#### Test 54970261e0c50c1_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  909): Waited long enough for: ServiceRecord{4413f340 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4379): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4379): ====startRecUseTime====
D/htc.customization.log.level( 4379):  is 
W/CustomizationLogLevel( 4379): Level value is invalid, use default level 2
D/CustomizationManager( 4379):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4379): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4379): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4379): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4379): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4379): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4379): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4379): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4379): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4379): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4379): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4379): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4379): Parsing tag category name = system
I/CustomizationCIDLoader( 4379): Parsing tag category name = application
I/CustomizationCIDLoader( 4379): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4379): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4379): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4379): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4379): Parsing tag category name = Settings
D/CustomizationManager( 4379):  Read CID file spent 0.098 (s)
D/CustomizationManager( 4379):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 4379): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4379): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4379): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4379): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4379
D/PMS     (  909): acquireHCC(41b05660): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(42326498): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1103708400
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bb0370
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
D/PMS     (  909): acquireWL(41aeef50): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4390 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4390): Binding Chromium to main looper Looper (main, tid 1) {41ae1080}
I/LibraryLoader( 4390): Expected native library version number "",actual native library version number ""
I/chromium( 4390): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4390): Initializing chromium process, renderers=0
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422db518:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4390): 1102020584: getState(). Returning 12
D/PMS     (  909): acquireWL(435e4cc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  909): acquireWL(42982770): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  909): releaseWL(435e4cc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/Adreno-EGL( 4390): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4390): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4390): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4390): Local Branch: 
I/Adreno-EGL( 4390): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4390): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4390):                  aa63bbd948f41d15fc72f585e
W/chromium( 4390): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4390): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4390): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4390): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4390): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4390): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4390): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4390): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4390): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4390): CordovaWebView is running on device made by: HTC
,W/AwContents( 4390): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  909): Disable input method client, pid=1270
,I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +248ms
W/ResourceType( 4390): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4390): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b29698, mServedView=org.apache.cordova.engine.SystemWebView{41aef300 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4390): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,I/InputMethodManagerService(  909): Enable input method client, pid=4390
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  909): releaseWL(41aeef50): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4390): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4390): JniHelper::setJavaVM(0x415ba048), pthread_self() = 1662516016
,D/JX-Cordova( 4390): jxcore cordova android initializing
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/dalvikvm-heap( 4390): Grow heap (frag case) to 11.532MB for 63974-byte allocation
,I/dalvikvm-heap( 4390): Grow heap (frag case) to 11.581MB for 95956-byte allocation
,I/dalvikvm-heap( 4390): Grow heap (frag case) to 11.660MB for 143930-byte allocation
,I/dalvikvm-heap( 4390): Grow heap (frag case) to 11.775MB for 215890-byte allocation
,I/dalvikvm-heap( 4390): Grow heap (frag case) to 11.950MB for 323830-byte allocation
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4390): Grow heap (frag case) to 12.625MB for 728606-byte allocation
,I/dalvikvm-heap( 4390): Grow heap (frag case) to 13.222MB for 1092904-byte allocation
,I/dalvikvm-heap( 4390): Grow heap (frag case) to 14.107MB for 1639352-byte allocation
,D/PMS     (  909): acquireWL(42550280): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,I/dalvikvm-heap( 4390): Grow heap (frag case) to 15.445MB for 2459024-byte allocation
,D/PMS     (  909): releaseWL(42550280): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(42496a90): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,E/libc    ( 4390): mmap fail (pid 4390, tid 4390, size 0, flags 0x1, errno 22(Invalid argument))
D/PMS     (  909): releaseWL(42496a90): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  909): acquireWL(424ff9a8): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  909): releaseWL(424ff9a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(425a7fd8): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  909): releaseWL(425a7fd8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4390): Grow heap (frag case) to 17.508MB for 3688532-byte allocation
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(41b05660): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(42326498): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4390): Initializing JXcore engine
,W/jxcore-log( 4390): JXcore engine is ready
,W/jxcore-log( 4390): Starting JXcore engine
,W/jxcore-log( 4390): Platform android
W/jxcore-log( 4390): 
,W/jxcore-log( 4390): Process ARCH arm
W/jxcore-log( 4390): 
,I/jxcore-log( 4390): JXcore Cordova bridge is ready!
I/jxcore-log( 4390): 
,W/jxcore-log( 4390): JXcore engine is started
,I/chromium( 4390): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4390): Toggling radios to true
I/jxcore-log( 4390): 
,D/BluetoothAdapter( 4390): enable(): BT is already enabled..!
,D/WifiManager( 4390): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 2
W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1102
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
,W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
,W/Settings:Agent(  909): << traceCallingStack(): 1(ms)
D/WifiManager( 4390): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  909): doBoolean: DISCONNECT
,D/WifiManager( 4390): reconnect: Base Package Name=com.test.thalitest, uid=10348
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): TDLS: Tear down peers
I/wpa_supplicant( 1159): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  909): setWifiEnabled: true pid=4390, uid=10348
D/WifiService(  909): New client listening to asynchronous messages
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4390): Radios toggled
I/jxcore-log( 4390): 
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4440 uid=10077 gids={50077}
,D/PMS     (  909): acquireWL(42364cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10077}
,V/AlarmManager(  909): sending alarm PendingIntent{4253b478: PendingIntentRecord{425c0dc0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452274458116, Int=60000
,D/PMS     (  909): releaseWL(42364cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1159): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1159): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
,D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1159): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7879bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1159):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1159): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1159): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 48 (NL80211_CMD_DISCONN,ECT) received for wlan0
D/wpa_supplicant( 1159): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  909):    returned true
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiPerfLock(  909): release()
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  909): acquireWL(4236d3d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  909): [RunningState] Stop DHCP
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909): doBoolean: RECONNECT
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20199 mDataStallAlarmIntent=PendingIntent{41bdf900: PendingIntentRecord{42587e78 android broadcastIntent}}
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): Fast associate: Old scan results
I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  909):    returned true
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  909): Enter handleNetworkDisconnect
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
,D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/WifiP2pService(  909): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1878/10178)
D/UsbnetStateTracker(  909): isAvailable+-
D/UsbnetStateTracker(  909): reconnect
,D/UsbnetStateTracker(  909): isAvailable+-
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/PMS     (  909): releaseWL(42982770): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3785): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3785): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  909): New client listening to asynchronous messages
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): Exit handleNetworkDisconnect
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/ConnectivityService(  909): resetConnections(wlan0, 3)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  365): [NET] entry_id:5   entry:0xb76b9190  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb76b92a0  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb76b9428  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb76b9860  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb76b8fd8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb76b90f8  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb76b9350  removed 
D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/SMSBackup( 4440): SMSBackupAgentService started
,D/SMSBackup( 4440): Checking restore status
,D/WISPrService( 3785): >>>>>WISPrService start isConnected = false<<<<<
D/SMSBackup( 4440): Restore complete
,D/SMSBackup( 4440): cancelCheckAlarm
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
D/PMS     (  909): acquireWL(4248ab08): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1878/10178)
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3785): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(44042be0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/PMS     (  909): acquireWL(4259af10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/SMSBackup( 4440): SMSBackupAgentService completed: completed in 0.0 seconds
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1371/10028)
,D/PMS     (  909): releaseWL(4259af10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
D/Process (  909): killProcessQuiet, pid=3149
D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  909):    returned false
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3149:com.android.defcontainer/u0a19 (adj 15): empty #17
D/BatSI   (  909): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  909): releaseWL(4248ab08): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  909): releaseWL(44042be0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  909): Recipient 3149
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  909): NoActiveNetworkState
,I/NetworkMonitor( 3855): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
,D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  909): ipv4Default null
I/Tethering(  909): No IPv4 upstream interface, giving up.
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/PMS     (  909): acquireWL(43c57f20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4280/10100)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3855/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4280/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1915/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1423/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1878/10178)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2426/10021)
,I/ActivityManager(  909): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4461 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4461): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4461): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4461): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4461): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4461): Preparing secondary program dexes.
V/DexLibLoader( 4461): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4461): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4461): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4461): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4461): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4461): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4461): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4461): Dex already copied
D/OdexVerifier( 4461): Odex verification is skipped.
,V/DexLibLoader( 4461): Creating class loader
,V/DexLibLoader( 4461): Finished creating class loader
V/DexLibLoader( 4461): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4461): Dex already copied
D/OdexVerifier( 4461): Odex verification is skipped.
,V/DexLibLoader( 4461): Creating class loader,
V/DexLibLoader( 4461): Finished creating class loader
V/DexLibLoader( 4461): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar,
V/DexLibLoader( 4461): Dex already copied
D/OdexVerifier( 4461): Odex verification is skipped.
,V/DexLibLoader( 4461): Creating class loader
,V/DexLibLoader( 4461): Finished creating class loader
V/DexLibLoader( 4461): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4461): Dex already copied
D/OdexVerifier( 4461): Odex verification is skipped.
,V/DexLibLoader( 4461): Creating class loader,
V/DexLibLoader( 4461): Finished creating class loader
,V/DexLibLoader( 4461): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4461): DexLibLoader.ensureDexLoaded took 17 ms
,D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  909): releaseWL(43c57f20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/dalvikvm( 4461): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4461): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4461): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4461): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4461): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4461): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4461): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4461): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1159): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-76
I/wpa_supplicant( 1159): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-82
I/wpa_supplicant( 1159): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=9 entropy=0
D/wpa_supplicant( 1159): Add randomness: count=10 entropy=1
D/wpa_supplicant( 1159): Add randomness: count=11 entropy=2
D/wpa_supplicant( 1159): Add randomness: count=12 entropy=3
D/wpa_supplicant( 1159): Add randomness: count=13 entropy=4
D/wpa_supplicant( 1159): Add randomness: count=14 entropy=5
D/wpa_supplicant( 1159): Add randomness: count=15 entropy=6
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1159): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 3
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): w,pa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 1
I/wpa_supplicant( 1159): wpa_s->is_screen_on 1
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): selected network = 1
D/wpa_supplicant( 1159): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb787b4e8  current_ssid=0x0
D/wpa_supplicant( 1159): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1159): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1159): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1159): check if in concurrent case
,I/wpa_supplicant( 1159): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1159): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1159): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1159): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1159): RSN: PMKSA cache search - network_ctx=0xb787b4e8 try_opportunistic=0
D/wpa_supplicant( 1159): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1159): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1159): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1159): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1159): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1159): nl80211: Unsubscribe mgmt frames handle 0xb787a718 (mode change)
,D/wpa_supplicant( 1159): nl80211: Subscribe to mgmt frames with non-AP handle 0xb787a718
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb787a718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb787a718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb787a718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb787a718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb787a718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb787a718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb787a718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb787a718
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb787a718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb787a718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1159):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1159):   * freq=2412
D/wpa_supplicant( 1159):   * Auth Type 0
D/wpa_supplicant( 1159):   * WPA Versions 0x2
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1159): nl80211: Connect request send successfully
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING,
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1159): reply (921) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-48
I/wpa_supplicant( 1159): tsf=0000000106281248
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-54
I/wpa_supplicant( 1159): tsf=0000000106281267
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-82
I/wpa_supplicant( 1159): tsf=0000000106281282
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=UPC5999698
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-76
I/wpa_supplicant( 1159): tsf=0000000022171370
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=4
I/wpa_supplicant( 1159): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-76
I/wpa_supplicant( 1159): tsf=0000000106281275
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1159): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-83
I/wpa_supplicant( 1159): tsf=0000000106281278
I/wpa_supplicant( 1159): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC Wi-Free
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=6
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-54
I/wpa_supplicant( 1159): tsf=0000000106281262
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 106281248, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 106281267, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (7) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 2: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -82, frequency: 2437, timestamp: 106281282, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 22171370, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -76, frequency: 2437, timestamp: 106281275, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -83, frequency: 2437, timestamp: 106281278, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 106281262, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 7 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/dalvikvm( 4461): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1159): nl80211: Connect event
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1159): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1159): Add randomness: count=16 entropy=7
I/wpa_supplicant( 1159): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1159): TDLS: Remove peers on association
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1159): EAPOL: enable timer tick
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1159): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1159): Get randomness: len=32 entropy=8
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantSt,ateChange(): SSIDNG700
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
D/WifiStateMachine(  909): Associated
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
D/WifiStateMachine(  909): BSSID was changed, update WiFi database
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1159): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb787a9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1159):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1159): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ef7b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1159):    broadcast key
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1159): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1159): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1159): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1159): set send_ind_to_ndc = 0
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1159): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1159): EAPOL authentication completed successfully
I/wpa_supplicant( 1159): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  909): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
E/FbInjectorInitializer( 4461): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WISPrService( 3785): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3785): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/DhcpStateMachine(  909): [StoppedState] Start DHCP
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(42538a70): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 1
I/wpa_supplicant( 1159): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  909):    returned null
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4246c5b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4246c5b8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4461): Verify
,D/WifiService(  909): New client listening to asynchronous messages
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4461): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4461): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  909): killProcessQuiet, pid=3837
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3837:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  909): acquireWL(440d6220): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
,I/ActivityManager(  909): Recipient 3837
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(42582e30): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1222 10028 null
,D/PMS     (  909): releaseWL(440d6220): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  909): releaseWL(42582e30): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1371): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/AutoSetting( 1435): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  909): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4490 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1435/10053)
,D/AutoSetting( 1435): Util - no network available!
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1435/10053)
D/AutoSetting( 1435): service - onCreate()
D/AutoSetting( 1435): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1435): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  909): request 42512810 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1435): service - mHandler: cancel location update
D/AutoSetting( 1435): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4461): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4461): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4461): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4490): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4490): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4490): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4490): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  909): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4506 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4490/10078)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4490/10078)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4490/10078)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4461): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/Process (  909): killProcessQuiet, pid=4222
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4523 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Killing 4222:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4222
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 9.958MB for 84664-byte allocation
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 4523): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4461): Grow heap (frag case) to 9.974MB for 28144-byte allocation
W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/dalvikvm( 4461): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4461): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4461): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4461): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4461): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4461): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4461): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4461): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4461): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4461): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4461): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4461): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4461): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4461): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4461): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4461): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 10.039MB for 39954-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 10.115MB for 79892-byte allocation
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4523/10151)
,V/WebViewChromiumFactoryProvider( 4523): Binding Chromium to main looper Looper (main, tid 1) {41ae7200}
,I/LibraryLoader( 4523): Expected native library version number "",actual native library version number ""
,I/chromium( 4523): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4523): Initializing chromium process, renderers=0
,D/PMS     (  909): acquireWL(43a671e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,D/PMS     (  909): acquireWL(440cb7c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,E/AudioManagerAndroid( 4523): BLUETOOTH permission is missing!
D/PMS     (  909): releaseWL(43a671e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4523): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4523): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4523): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4523): Local Branch: 
I/Adreno-EGL( 4523): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4523): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4523):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4523): Starting up...
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4523/10151)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4523/10151)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4153/10160)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4153/10160)
,D/Process (  909): killProcessQuiet, pid=4250
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 10.280MB for 75760-byte allocation
I/ActivityManager(  909): Killing 4250:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1878/10178)
I/ActivityManager(  909): Recipient 4250
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1878/10178)
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4350ec30 u0 ReceiverList{4350eb10 4461 com.facebook.katana/10026/u0 remote:434fa288}}
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4350ec30 u0 ReceiverList{4350eb10 4461 com.facebook.katana/10026/u0 remote:434fa288}}
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43775350 u0 ReceiverList{437752f0 4461 com.facebook.katana/10026/u0 remote:43712a88}}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/PMS     (  909): acquireWL(43807280): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1423 10028 null
,D/PMS     (  909): releaseWL(43807280): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1423): Unknown pending intent to remove.
D/PMS     (  909): acquireWL(42575a00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1423 10028 null
D/PMS     (  909): releaseWL(42575a00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4461): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4461): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1159): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1159): EAPOL: disable timer tick
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61,
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2,
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  909): releaseWL(42538a70): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): gateway: /192.168.1.1
D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20201 delay=15s
,D/WifiWatchdogStateMachine(  909): WAN detection
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1878/10178)
D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3785): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@42410b18
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(42f48ef0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4490/10078)
,D/PMS     (  909): acquireWL(432388e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/PMS     (  909): acquireWL(434b9b68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1222 10028 null
D/PMS     (  909): releaseWL(432388e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
I/CheckinService( 1222): Preparing to send checkin request
I/EventLogService( 1222): Accumulating logs since 1452274409421
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1222): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1222): Using GMS GoogleHttpClient
D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (1222/10028)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (1222/10028)
D/PMS     (  909): releaseWL(42f48ef0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1608): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1608): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1222): awaiting user notification for token
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41fb7a68 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 0 17 5 12
,I/ActivityManager(  909): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4598 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4598): install
,I/MultiDex( 4598): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4598): loading existing secondary dex files
,I/MultiDex( 4598): load found 1 secondary dex files
,I/MultiDex( 4598): install done
,I/ProviderInstaller( 4598): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SensorManager(  909): mEventCount = 1200
,I/Adreno-EGL( 4598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4598): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4598): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4598): Local Branch: 
I/Adreno-EGL( 4598): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4598): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4598):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4598): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4598): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4598): Local Branch: 
I/Adreno-EGL( 4598): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4598): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4598):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1117): WifiActivity: 2
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  909): releaseWL(4236d3d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4280/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1878/10178)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1423/10028)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  909): bSetPropertyMultiRAB:false
,D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/NetworkMonitor( 3855): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  909): NoActiveNetworkState
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4490/10078)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3855/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1915/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.musicenhancer (3876/10051)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4280/10100)
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): Found interface wlan0
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4373d500): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4373c238): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1915): Checking Certificates
I/acms    ( 1915): Checking Developer Certificates
I/acms    ( 1915): Checking Application Certificates
I/acms    ( 1915): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1915): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1915): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1915): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1915): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1915): Updating next query delay: 75600000
I/mlserverapp( 1915): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1915): cancelACMSProgrammedChecks
,D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(4373c238): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  909): releaseWL(4373d500): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2426/10021)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(41ce2cc0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(41ce2cc0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1371): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1371): [NET] getaddrinfo-,err=8
D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1371): [NET] getaddrinfo-, 1
D/libc    ( 1371): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =8efa +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  909): acquireWL(41d5c208): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1371 10028 null
D/AutoSetting( 1435): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4490): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4490): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1435): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1435/10053)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4523/10151)
D/AutoSetting( 1435): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1435): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1435): service - onStartCommand() REMOVE current location bundle
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1435): service - handleMessage() setting current location null
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1435/10053)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4153/10160)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4153/10160)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1435): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1435): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1878/10178)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 100
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1371): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4153): Grow heap (frag case) to 13.516MB for 1821008-byte allocation
,D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1371): [NET] getaddrinfo-,err=8
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  909): acquireWL(42656d50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  909): releaseWL(42656d50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4598): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4598): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4598): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4598): Local Branch: 
I/Adreno-EGL( 4598): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4598): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4598):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): acquireWL(424ec1c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
D/GCM     ( 1371): Connected
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=14 [7][1][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  909): BroadcastRSSIForIMS, newrssi =-54 , oldRssi= -200
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  909): releaseWL(41d5c208): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  909): releaseWL(424ec1c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4598/10028)
,D/PMS     (  909): acquireWL(425a4e98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/GCM     ( 1371): Message class mpf
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  909): acquireWL(422f12c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  909): releaseWL(425a4e98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  909): releaseWL(422f12c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/fb4a(:<default>):UserScope( 4461): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4461): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
I/CheckinTask( 1222): Sending checkin request (9021 bytes)
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a9af +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 250
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4461): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=46 [13][6][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  909): releaseWL(440cb7c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  909): acquireWL(43b770f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  909): releaseWL(43b770f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (1222/10028)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [2][0][0]
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1608): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1608): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1222): awaiting user notification for token
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41af0848 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 2 6 3 12
,I/CheckinTask( 1222): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1222): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  909): releaseWL(434b9b68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 1222): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cb2208 that was originally bound here
E/ActivityThread( 1222): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cb2208 that was originally bound here
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
,I/GCM     ( 1371): GCM config loaded
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42058d48
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42058d48, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42178ca0
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@425fa588
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,W/PMS     (  909): mWirelessDisplayManager is null
D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 374ms
D/NfcService( 1249): ScreenObserver: OFF
,D/NfcService( 1249): applyRouting - 0
I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1249): applyRouting -2
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/PMS     (  909): OOBE c monitor 11
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=4390
D/PMS     (  909): acquireWL(42baa2d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1249 1027 null
D/PMS     (  909): releaseWL(42baa2d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42510b78)
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
D/PMN     (  909): wakingUp
I/WindowManager(  909): No lock screen! windowToken=null
D/PMN     (  909): onScreenOn
,D/PMS     (  909): acquireWL(43541cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1608): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(43541cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/MtpService( 2426): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2426): [MTP][onReceive]-
,D/NfcService( 1249): applyRouting - 0
,D/AutoSetting( 1435): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1249): applyRouting -2
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): acquireWL(43647ba8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1249 1027 null
D/TetherSettings( 3785): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3785): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3785): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3785): Cust_ConnectToPC   : spcsc>false
D/        ( 3785): Cust_ConnectToPC   : IPT>true
,D/        ( 3785): Cust_ConnectToPC   : Singel_USB>false
D/AutoSetting( 1435): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
W/Settings( 3785): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,E/SmartNS_Utility( 3785): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3785): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3785): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20202 delay=15s
,I/ClockThread( 1117): stop update clock
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/PMS     (  909): releaseWL(43647ba8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
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
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
I/PSReceiver( 3785): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:On
I/wpa_supplicant( 1159): htc_wext_set_keepalive +,
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6,
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/SmartNS_PSService( 3785): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3785): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3785):  defaultType:0
W/ContextImpl( 3785): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  373): ParamSet string: screen_state=on
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false,
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/NetworkPolicy(  909): updateScreenOn: false
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4639 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6b9 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/104.81.130.175
,D/DotMatrix( 1608): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1850): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): onScreenOn: 1452274465323
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1850): onScreenOn: 1452274465323
D/PMS     (  909): acquireWL(425e65b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1423 10028 null
D/PMS     (  909): releaseWL(425e65b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42178ca0
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42178ca0, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@425fa588
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  909): goingToSleep
W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  909): acquireWL(437ee6a8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20202 mDataStallAlarmIntent=PendingIntent{435e4f68: PendingIntentRecord{42587e78 android broadcastIntent}}
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:Off
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1159): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
D/PMS     (  909): acquireWL(44068c88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4639 1000 null
,D/PMS     (  909): acquireWL(41ad8278): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
V/SRS_Proc(  373): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4639): isEpsOn(), nState = 0
D/NetworkPolicy(  909): updateScreenOn: false
,D/ContactMessageStore( 1238): start background delete task...
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
D/PMS     (  909): releaseWL(44068c88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(41ad8278): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/SmartSyncUtils( 4639): getMobilePolicyEnabled, result = true
,D/Process (  909): killProcessQuiet, pid=4280
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Killing 4280:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,I/ActivityManager(  909): Recipient 4280
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4639): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4639): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4639): isEpsOn(), nState = 0
D/WifiService(  909): New client listening to asynchronous messages
,D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1608): [EventService] getTotalRam: 1873 Mb
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425fa588
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425fa588, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425fa588, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425fa588
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1850): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1850): onScreenOff
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  909): acquireWL(43801850): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1423 10028 null
D/PMS     (  909): releaseWL(43801850): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425fa920 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425fa920 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1435): service - mHandler: cancel location update
,D/AutoSetting( 1435): service -           changes count: 0
,W/ActivityManager(  909): Activity pause timeout for ActivityRecord{4228c2a0 u0 com.test.thalitest/.MainActivity t2}
,I/GAV2    ( 4523): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  909): acquireWL(43bb8348): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1423 10028 null
,D/PMS     (  909): acquireWL(43f9d510): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1423 10028 null
,D/PMS     (  909): releaseWL(43bb8348): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  909): releaseWL(43f9d510): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/jxcore-log( 4390): Test app app.js loaded
I/jxcore-log( 4390): 
,I/Choreographer( 4390): Skipped 534 frames!  The application may be doing too much work on its main thread.
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ResourceType( 4390): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4390): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aef300 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  909): releaseWL(437ee6a8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4390): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  909): killProcessQuiet, pid=4303
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4303:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4303
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1518): service - handleMessage() stop self
,D/AutoSetting( 1518): service - onDestroy() END
,D/AutoSetting( 1518): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4320
,I/ActivityManager(  909): Killing 4320:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4320
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4461/10026)
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{43662cb8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(44076578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1608): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(44076578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1435): service - mHandler: update timezone
,D/AutoSetting( 1518): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1518): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1518): service - onCreate(),
,W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1518): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1518): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1518): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1518): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1518): service - mHandler: update timezone
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1608): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1608): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1518): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1518): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1518): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1518): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1608): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,I/PhoneStatusBar( 1117): removeNotification.gc:51
,D/DotMatrix( 1608): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c3dca8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 8 2 11
,D/AutoSetting( 1435): service - handleMessage() stop self
,D/AutoSetting( 1435): service - onDestroy() END
,D/AutoSetting( 1435): service - handleMessage() quit looper
,D/PMS     (  909): acquireWL(44149de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10028}
,V/AlarmManager(  909): sending alarm PendingIntent{44026d88: PendingIntentRecord{424da8e0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141461, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{423127f0: PendingIntentRecord{423cd938 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141701, Int=0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(440c8790): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): acquireWL(440c3aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  909): releaseWL(44149de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  909): releaseWL(440c3aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e0ab +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 33
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success,
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  909): acquireWL(4405c4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{420f8768: PendingIntentRecord{42350398 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=145986, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4405c4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): releaseWL(440c8790): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  909): killProcessQuiet, pid=3876
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3876:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3876
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{4313e4f8 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1518): service - handleMessage() stop self
,D/AutoSetting( 1518): service - onDestroy() END
,D/AutoSetting( 1518): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4267
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4267:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4267
,D/PMS     (  909): acquireWL(438751e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(438751e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1608): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus,
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(43749aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43749aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43743cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{420f8768: PendingIntentRecord{42350398 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=205986, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43743cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43741390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10026}
,V/AlarmManager(  909): sending alarm PendingIntent{435f5a50: PendingIntentRecord{440d02b8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227277, Int=0
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4680 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{425265a8: PendingIntentRecord{424760b8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452274574815, Int=10800000
,D/PMS     (  909): releaseWL(43741390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4680/10047)
,D/Process (  909): killProcessQuiet, pid=4339
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4339:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4339
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  909): acquireWL(43732b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1608): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(43732b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42f470f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10026}
,V/AlarmManager(  909): sending alarm PendingIntent{4257ab78: PendingIntentRecord{440d02b8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231349, Int=0
,D/PMS     (  909): releaseWL(42f470f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(424971d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(424971d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1608): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(41c09820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{420f8768: PendingIntentRecord{42350398 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=265986, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(41c09820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(42303210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  909): releaseWL(42303210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1608): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1608): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4390): ****TEST TOOK:  ms ****
I/jxcore-log( 4390): 
,I/jxcore-log( 4390): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4390): 
,E/cutils-trace( 4704): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4704): ====startRecUseTime====
D/htc.customization.log.level( 4704):  is 
,W/CustomizationLogLevel( 4704): Level value is invalid, use default level 2
,D/CustomizationManager( 4704):  Read ACC file spent 0.101 (s)
D/CIDMapFileReader( 4704): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4704): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4704): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4704): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4704): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4704): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4704): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4704): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4704): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4704): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4704): full path : /system/customize/CID/HTC__032.xml,
I/CustomizationCIDLoader( 4704): Parsing tag category name = system
I/CustomizationCIDLoader( 4704): Parsing tag category name = application,
I/CustomizationCIDLoader( 4704): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4704): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4704): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4704): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4704): Parsing tag category name = Settings
,D/CustomizationManager( 4704):  Read CID file spent 0.153 (s)
,D/CustomizationManager( 4704):  All configurations done spent 0.153 (s)
,W/HtcNativeFlag( 4704): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4704): Fail to get flag for type 'customer', use default value: -1
,W/HtcNativeFlag( 4704): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4704): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4704, uid=2000 user=0
,I/ActivityManager(  909): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
,D/Process (  909): killProcessQuiet, pid=4390
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  909): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  909): Killing 4390:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  909):   Force finishing activity ActivityRecord{4228c2a0 u0 com.test.thalitest/.MainActivity t2}
,W/InputDispatcher(  909): channel '423a4478 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  909): channel '423a4478 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  909): Attempted to unregister already unregistered input channel '423a4478 com.test.thalitest.MainActivity (s)'
I/WindowManager(  909): WINDOW DIED Window{423a4478 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
W/WindowManager(  909): Failed looking up window
W/WindowManager(  909): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@423fdc00 does not exist
W/WindowManager(  909): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  909): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  909): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  909): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  909): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  909): WIN DEATH: null
,W/PackageSettings(  909): Skipping PackageSetting{422bb948 com.example.hello/10356} due to missing metadata
,W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 4390 uid 10348
,W/Binder  ( 1209): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1209): java.lang.NullPointerException
W/Binder  ( 1209): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1209): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1209): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1209): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  909): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
,I/dalvikvm-heap( 4153): Grow heap (frag case) to 15.213MB for 1821008-byte allocation
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1608): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1608): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1608): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,I/acms    ( 1915): Unregistering com.test.thalitest
,E/acms    ( 1915): Could not unregister removed application com.test.thalitest
,W/GeofencerStateMachine( 1423): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): acquireWL(436e6690): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1423 10028 null
D/PMS     (  909): releaseWL(436e6690): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/PackageBroadcastService( 1222): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/Launcher( 1270): Deferring update until onResume
,D/Launcher( 1270): waitUntilResume // bindAppsRemoved
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/ActivityManager(  909): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4719 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/SystemReader( 1249): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/MultiDex( 4719): install
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
,I/MultiDex( 4719): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4719): loading existing secondary dex files
I/ActivityManager(  909): Delaying start of: ServiceRecord{43f67498 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/MultiDex( 4719): load found 1 secondary dex files
I/MultiDex( 4719): install done
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/ActivityManager(  909): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4735 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/PeopleContactsSync( 1222): CP2 sync disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1222, uid=10028, userID:0
,I/ProviderInstaller( 4719): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/Icing   ( 1222): doRemovePackageData com.test.thalitest
D/PMS     (  909): acquireWL(431e21c0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  909): releaseWL(431e21c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4735): install
I/MultiDex( 4735): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4735): loading existing secondary dex files
,I/MultiDex( 4735): load found 1 secondary dex files
,I/MultiDex( 4735): install done
,I/ProviderInstaller( 4735): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  909): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1435): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1435): handle notify Blinkfeed plugin client changed
,D/Process (  909): killProcessQuiet, pid=4353
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  909): Killing 4353:com.android.settings:remote/1000 (adj 15): empty #17
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 2878): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4755 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/ActivityManager(  909): Recipient 4353
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(435dbcb0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  909): releaseWL(435dbcb0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(4236d3f0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,I/IcingCorporaProvider( 2878): UpdateCorporaTask done [took 181 ms] updated apps [took 181 ms] 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4719): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4719/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4719/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4719/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4719/10028)
,W/PackageManager(  909): Unable to load service info ResolveInfo{42560d10 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,E/SQLiteDatabase( 4755): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4755): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4755): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4755): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4755): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4755): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4755): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4755): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4755): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4755): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4755): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4755): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4755): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4755): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4755): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4755): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4755): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4755): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4755): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4755): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4755): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4755): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4755): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4755): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4755): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4755): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4755): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4755): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4755): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4755): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4755): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4755): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4755): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4755): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4755): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4755): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4755): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4755): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4755): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4755): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4755): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4755): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4755): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4755): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4755): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4755): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4755): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4755): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4755): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4755): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4755): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4755): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4755): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4755): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4755): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4755): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4755): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4755): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4755): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4755): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4755): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4755): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4755): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4755): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4755): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4755): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4755): threadid=11: thread exiting with uncaught exception (group=0x416b2e30)
E/AndroidRuntime( 4755): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4755): Process: com.google.android.apps.docs, PID: 4755
E/AndroidRuntime( 4755): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4755): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4755): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4755): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4755): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4755): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4755): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4755): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
,E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
E/SQLiteDatabase( 4755): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4755): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4755): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4755): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4755): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4755): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4755): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4755): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4755): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4755): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4755): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4755): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4755): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4755): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4755): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4755): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4755): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4755): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4755): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4755): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4755): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4755): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4755): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4755): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4755): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4755): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4755): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4755): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4755): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4755): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4755): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4755): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4755): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4755): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4755): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4755): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4755): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4755): Opened ClientFlag.db in read-only mode
D/Process ( 4755): killProcess, pid=4755
D/Process ( 4755): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/RemoteDisplayProvider(  909): start
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4779 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4755
,D/Process (  909): killProcessQuiet, pid=4000
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4000:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  909): Process com.google.android.apps.docs (pid 4755) has died.
,W/AtomicFile(  909): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  909): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,W/ContextImpl( 4779): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4779): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4779): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4779): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4779): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4779): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4779): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4779): threadid=10: thread exiting with uncaught exception (group=0x416b2e30)
E/AndroidRuntime( 4779): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4779): Process: com.android.keychain, PID: 4779
E/AndroidRuntime( 4779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4779): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4779): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4779): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4779): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4779): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  909): App crashed! Process: com.android.keychain
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4792 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
,E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452274651743.dbox_tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 4779): killProcess, pid=4779
,D/Process ( 4779): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  909): Recipient 4779
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Process com.android.keychain (pid 4779) has died.,
,W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/AppTag  ( 4792): getInstance(Context context)
,D/AppTag  ( 4792): getInstance(Context context)
,D/AppTag  ( 4792): onCreate()
,I/ActivityManager(  909): Recipient 4000
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(422f1f00): PARTIAL_WAKE_LOCK  AsyncService 0x1 4153 10160 null
,I/dalvikvm-heap( 4153): Grow heap (frag case) to 16.948MB for 1821008-byte allocation
D/PMS     (  909): releaseWL(422f1f00): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  909): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4810 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4810): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4810 dbg=false s=true
,I/DeviceManagement( 4810): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4810): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4810): WorkflowService: Starting workflow service
I/DeviceManagement( 4810): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b14038] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4810): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4810): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4810): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4810): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  909): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4824 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4810): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4810): SessionStateController: Checking invariants...
,D/Documents( 4824): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4824): Loading roots for com.android.externalstorage.documents
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b75f10 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,E/SQLiteDatabase( 4824): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4824): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4824): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4824): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4824): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4824): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4824): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4824): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4824): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4824): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4824): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4824): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4824): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4824): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4824): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4824): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4824): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4824): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4824): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4824): threadid=1: thread exiting with uncaught exception (group=0x416b2e30)
,E/AndroidRuntime( 4824): FATAL EXCEPTION: main
E/AndroidRuntime( 4824): Process: com.android.documentsui, PID: 4824
E/AndroidRuntime( 4824): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4824): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4824): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4824): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4824): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4824): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4824): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4824): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4824): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4824): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4824): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4824): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4824): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4824): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4824): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4824): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4824): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4824): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4824): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4824): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4824): 	... 10 more
,I/ActivityManager(  909): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4838 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  909): killProcessQuiet, pid=4440
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  909): Killing 4440:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,E/ActivityManager(  909): App crashed! Process: com.android.documentsui
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  909): Killing 3855:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/Process (  909): killProcessQuiet, pid=3855
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4440
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452274652087.dbox_tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 4824): killProcess, pid=4824
,D/Process ( 4824): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3855
D/MediaRouterService(  909): Client com.google.android.music (pid 3855): Died!
I/ActivityManager(  909): Recipient 4824
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Process com.android.documentsui (pid 4824) has died.
,I/ActivityManager(  909): Resuming delayed broadcast
,E/SQLiteDatabase( 4810): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
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
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4810): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4810): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4810): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4810): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4810): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4810): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4810): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4810): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4810): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4810): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4810): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4810): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4810): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4810): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4810): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4810): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4810): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ExternalStorage( 4838): After updating volumes, found 1 active roots
,E/SQLiteDatabase( 4810): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
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
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4810): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4810): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4810): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4810): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4810): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4810): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4810): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4810): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/DeviceManagement( 4810): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b14038]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4810): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4810): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4810): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4810): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4810): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4810): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4810): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4810): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 4810): WorkflowService: Stopping workflow service
,I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4854 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4854): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4854): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4854): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4854): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4854): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4854): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4854): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4854): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4854): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4854): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4854): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4854): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4854): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4854): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4854): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4854): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4854): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4854): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4854): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4854): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4854): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4854): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4854): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4854): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4854): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4854): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4854): Opened MyDB.db in read-only mode
,I/Icing   ( 1222): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
,D/Process (  909): killProcessQuiet, pid=4490
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4490:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4490
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Icing   ( 1222): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,E/Icing   ( 1222): Could not init tag ds.tag.deleted
,I/Icing   ( 1222): Indexing done 3E78574859FB8ED28F43D3ECB139F4117F00AB29
D/PMS     (  909): releaseWL(4236d3f0): PARTIAL_WAKE_LOCK  Icing 0x1 null

```
