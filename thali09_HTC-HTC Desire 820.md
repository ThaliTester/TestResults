#### Test 54970261e0c50c1_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/SMSBackup( 4377): SMSBackupAgentService completed: completed in 0.0 seconds
--------- beginning of /dev/log/system
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/Finsky  ( 4055): [425] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4055): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  905): killProcessQuiet, pid=3830
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3830:com.google.android.music:main/u0a154 (adj 15): empty #17
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3830
D/MediaRouterService(  905): Client com.google.android.music (pid 3830): Died!
E/cutils-trace( 4396): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4396): ====startRecUseTime====
D/htc.customization.log.level( 4396):  is 
W/CustomizationLogLevel( 4396): Level value is invalid, use default level 2
D/CustomizationManager( 4396):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4396): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4396): Parsing tag category name = system
I/CustomizationCIDLoader( 4396): Parsing tag category name = application
I/CustomizationCIDLoader( 4396): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4396): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4396): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4396): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4396): Parsing tag category name = Settings
D/CustomizationManager( 4396):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4396):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4396): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4396): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4396): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4396): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4396
D/PMS     (  905): acquireHCC(437d4f68): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(437d2938): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1141813616
I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d4efd8
I/SocialFeedProvider( 1268): +onPause
I/SocialFeedProvider( 1268): -onPause
D/PMS     (  905): acquireWL(437cfa68): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4407 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1268): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4407): Binding Chromium to main looper Looper (main, tid 1) {41b0ffa0}
I/LibraryLoader( 4407): Expected native library version number "",actual native library version number ""
I/chromium( 4407): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4407): Initializing chromium process, renderers=0
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42501158:true
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  905): acquireWL(4313b2e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  905): acquireWL(4313b0f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  905): releaseWL(4313b2e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4407): 1102208536: getState(). Returning 12
I/Adreno-EGL( 4407): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4407): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4407): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4407): Local Branch: 
I/Adreno-EGL( 4407): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4407): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4407):                  aa63bbd948f41d15fc72f585e
V/LightsService(  905): setLight #0: color=#24
W/chromium( 4407): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4407): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4407): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4407): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4407): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4407): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4407): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4407): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4407): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4407): CordovaWebView is running on device made by: HTC
V/LightsService(  905): setLight #0: color=#21
V/LightsService(  905): setLight #0: color=#17
,V/LightsService(  905): setLight #0: color=#14
I/SensorManager(  905): mEventCount = 1050
W/AwContents( 4407): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  905): Disable input method client, pid=1268
W/ResourceType( 4407): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4407): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b574c8, mServedView=org.apache.cordova.engine.SystemWebView{41b1d130 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  905): Enable input method client, pid=4407
W/AwContents( 4407): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +285ms
D/PMS     (  905): releaseWL(437cfa68): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4407): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4407): JniHelper::setJavaVM(0x415ea048), pthread_self() = 1662715016
D/JX-Cordova( 4407): jxcore cordova android initializing
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 11.556MB for 63974-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 11.610MB for 95956-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 11.692MB for 143930-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 11.811MB for 215890-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 11.979MB for 323830-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 12.628MB for 728606-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 13.222MB for 1092904-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 14.130MB for 1639352-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 15.461MB for 2459024-byte allocation
,E/libc    ( 4407): mmap fail (pid 4407, tid 4407, size 0, flags 0x1, errno 22(Invalid argument))
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(437d4f68): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(437d2938): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 13
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 32
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1154): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 17.484MB for 3688532-byte allocation
,W/jxcore-log( 4407): Initializing JXcore engine
,W/jxcore-log( 4407): JXcore engine is ready
,W/jxcore-log( 4407): Starting JXcore engine
,W/jxcore-log( 4407): Platform android
W/jxcore-log( 4407): 
,W/jxcore-log( 4407): Process ARCH arm
W/jxcore-log( 4407): 
,D/PMS     (  905): releaseWL(4313b0f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4407): JXcore Cordova bridge is ready!
I/jxcore-log( 4407): 
,W/jxcore-log( 4407): JXcore engine is started
,I/Choreographer( 4407): Skipped 162 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4407): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4407): Toggling radios to true
I/jxcore-log( 4407): 
,D/BluetoothAdapter( 4407): enable(): BT is already enabled..!
,D/WifiManager( 4407): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1381
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4407, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 2(ms)
D/WifiManager( 4407): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4407): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1154): TDLS: Tear down peers
I/wpa_supplicant( 1154): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4407): Radios toggled
I/jxcore-log( 4407): 
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1154): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1154): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1154): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
,D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1154): TDLS: Remove peers on disassociation
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1154): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1154): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1154): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1154): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7aa2bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1154):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1154): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1154): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1154): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1154): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1154): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1154): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1154): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1154): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1154): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1154): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1154): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1154): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1154): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1154): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1154): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1154): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1154): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1154): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1154): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1154): RTM_NEWLINK: operstate=0 ifi_flags=0x,1043 ([UP][RUNNING])
D/wpa_supplicant( 1154): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1154): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1154): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1154): nl80211: Event message available
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1154): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1154): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1154): Power_Mode_Type mode = 0
I/wpa_supplicant( 1154): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 61
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  905):    returned true
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  905): acquireWL(4258f558): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null,
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/WifiP2pService(  905): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20730 mDataStallAlarmIntent=PendingIntent{426a4188: PendingIntentRecord{425d2a80 android broadcastIntent}}
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1154): Fast associate: Old scan results
I/wpa_supplicant( 1154): wpa_supplicant_scan enter
I/wpa_supplicant( 1154): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1154): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1154): wpa_supplicant_trigger_scan +
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1154): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1154): nl80211: Event message available
D/wpa_supplicant( 1154): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1154): Power_Mode_Type mode = 0
I/wpa_supplicant( 1154): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WISPrService( 3775): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiService(  905): New client listening to asynchronous messages
I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3775): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1350): Read error: ssl=0x6403a0f8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1350): SSL shutdown failed: ssl=0x6403a0f8: I/O error during system call, Broken pipe
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/PMS     (  905): acquireWL(4257c298): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
D/libc    (  362): [NET] entry_id:3   entry:0xb7791d68  removed 
D/libc    (  362): [NET] entry_id:4   entry:0xb7791c38  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb7791f70  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb7791ea0  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb778d408  removed 
D/libc    (  362): [NET] entry_id:6   entry:0xb778d868  removed 
,D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 3775): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4268f780): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3775): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I//system/bin/ip(  362): RTNETLINK answers: No such process
I/logwrapper(  362): /system/bin/ip terminated by exit(2)
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/WifiNative-wlan0(  905): doBoolean: SCAN
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1154): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1350/10029)
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/PMS     (  905): releaseWL(4257c298): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905):    returned false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  905): releaseWL(4268f780): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4459 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  905): bSetPropertyMultiRAB:false
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/PMS     (  905): acquireWL(42603fa0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(42603fa0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  905): NoActiveNetworkState
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4258/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4258/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,I/MusicStore( 4459): Database version: 95
,W/ContextImpl( 4459): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4459): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4459): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4459): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4459): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4459, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 4459): Registered
,I/MediaRouter( 4459): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4459/10154)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2364/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4479 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4459): getSelectedRoute
,I/NetworkMonitor( 4459): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4459/10154)
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4459, uid=10154, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(44164bb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/Process (  905): killProcessQuiet, pid=4173
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 4173:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ACRA    ( 4479): ACRA is enabled for com.facebook.katana, intializing...
D/ACRA    ( 4479): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4479): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/PMS     (  905): releaseWL(44164bb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/SystemClassLoaderAdder( 4479): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4479): Preparing secondary program dexes.
V/DexLibLoader( 4479): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4479): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4479): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4479): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4479): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4479): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4479): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4479): Dex already copied
D/OdexVerifier( 4479): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4479): Creating class loader
,V/DexLibLoader( 4479): Finished creating class loader
,V/DexLibLoader( 4479): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4479): Dex already copied
D/OdexVerifier( 4479): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4479): Creating class loader
,V/DexLibLoader( 4479): Finished creating class loader
V/DexLibLoader( 4479): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4479): Dex already copied
D/OdexVerifier( 4479): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4479): Creating class loader
,V/DexLibLoader( 4479): Finished creating class loader
V/DexLibLoader( 4479): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4479): Dex already copied
D/OdexVerifier( 4479): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4479): Creating class loader
,V/DexLibLoader( 4479): Finished creating class loader
,V/DexLibLoader( 4479): Verifying classes from secondary dexes.
I/ActivityManager(  905): Recipient 4173
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DexLibLoader( 4479): DexLibLoader.ensureDexLoaded took 19 ms
,W/dalvikvm( 4479): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1154): nl80211: Event message available
D/wpa_supplicant( 1154): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1154): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1154): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1154): nl80211: Survey data missing
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1154): Sorted scan results
I/wpa_supplicant( 1154): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1154): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1154): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1154): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1154): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-87
D/wpa_supplicant( 1154): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1154): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1154): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1154): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1154): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1154): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1154): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1154): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1154): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1154): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1154): wpa_supplicant_pick_network+
I/wpa_supplicant( 1154): Selecting BSS from priority group 1
I/wpa_supplicant( 1154): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1154): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1154): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1154): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1154): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1154):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1154):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1154): Start print parameters
I/wpa_supplicant( 1154): wpa_s->wpa_state is 3
I/wpa_supplicant( 1154): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1154): isConcurrentMode() is 0
I/wpa_supplicant( 1154): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1154): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1154): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1154): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1154): wpa_s->reassociate is 1
I/wpa_supplicant( 1154): wpa_s->is_screen_on 1
I/wpa_supplicant( 1154): wpa_s->ifname wlan0
I/wpa_supplicant( 1154): End print parameters
I/wpa_supplicant( 1154): selected network = 1
D/wpa_supplicant( 1154): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:0,0:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7aa44e8  current_ssid=0x0
D/wpa_supplicant( 1154): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1154): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1154): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1154): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1154): check if in concurrent case
I/wpa_supplicant( 1154): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1154): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1154): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1154): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1154): RSN: PMKSA cache search - network_ctx=0xb7aa44e8 try_opportunistic=0
D/wpa_supplicant( 1154): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1154): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1154): State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1154): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1154): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1154): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1154): nl80211: Unsubscribe mgmt frames handle 0xb7aa3718 (mode change)
,D/wpa_supplicant( 1154): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7aa3718
D/wpa_supplicant( 1154): nl80211: Register frame type=0xd0 nl_handle=0xb7aa3718
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1154): nl80211: Register frame type=0xd0 nl_handle=0xb7aa3718
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1154): nl80211: Register frame type=0xd0 nl_handle=0xb7aa3718
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1154): nl80211: Register frame type=0xd0 nl_handle=0xb7aa3718
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1154): nl80211: Register frame type=0xd0 nl_handle=0xb7aa3718
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1154): nl80211: Register frame type=0xd0 nl_handle=0xb7aa3718
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1154): nl80211: Register frame type=0xd0 nl_handle=0xb7aa3718
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1154): nl80211: Register frame type=0xd0 nl_handle=0xb7aa3718,
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1154): nl80211: Register frame type=0xd0 nl_handle=0xb7aa3718
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1154): nl80211: Register frame type=0xd0 nl_handle=0xb7aa3718
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1154): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1154):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1154):   * freq=2412
D/wpa_supplicant( 1154):   * Auth Type 0,
D/wpa_supplicant( 1154):   * WPA Versions 0x2
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1154): nl80211: Connect request send successfully
D/wpa_supplicant( 1154): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1154): EAPOL: External notification - EAP fail=0,
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1154): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1154): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1154): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1154): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1154): reply (631) for get BSS: id=0,
I/wpa_supplicant( 1154): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1154): freq=5220
I/wpa_supplicant( 1154): level=-47
I/wpa_supplicant( 1154): tsf=0000000102731235
I/wpa_supplicant( 1154): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1154): ssid=NG7005g
I/wpa_supplicant( 1154): ====
I/wpa_supplicant( 1154): id=1
I/wpa_supplicant( 1154): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1154): freq=2412
I/wpa_supplicant( 1154): level=-56
I/wpa_supplicant( 1154): tsf=0000000102731252
I/wpa_supplicant( 1154): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1154): ssid=NG700
I/wpa_supplicant( 1154): ====
I/wpa_supplicant( 1154): id=2
I/wpa_supplicant( 1154): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1154): freq=2412
I/wpa_supplicant( 1154): level=-56
I/wpa_supplicant( 1154): tsf=0000000102731248,
I/wpa_supplicant( 1154): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1154): ssid=01ABC
I/wpa_supplicant( 1154): ====
I/wpa_supplicant( 1154): id=3
I/wpa_supplicant( 1154): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1154): freq=2412
I/wpa_supplicant( 1154): level=-76
I/wpa_supplicant( 1154): tsf=0000000102731255
I/wpa_supplicant( 1154): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1154): ssid=Gonzos
I/wpa_supplicant( 1154): ====
I/wpa_supplicant( 1154): id=4
I/wpa_supplicant( 1154): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1154): freq=2437
I/wpa_supplicant( 1154): level=-87
I/wpa_supplicant( 1154): tsf=0000000102731258
I/wpa_supplicant( 1154): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1154): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1154): ####
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 102731235, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiManager( 1219): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 102731252, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 102731248, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 102731255, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -87, frequency: 2437, timestamp: 102731258, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/wpa_supplicant( 1154): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1154): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1154): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1154): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1154): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1154): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1154): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1154): nl80211: Event message available
D/wpa_supplicant( 1154): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1154): nl80211: Connect event
D/wpa_supplicant( 1154): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1154): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1154): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1154): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1154): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1154): Add randomness: count=12 entropy=5
I/wpa_supplicant( 1154): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1154): TDLS: Remove peers on association
D/wpa_supplicant( 1154): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1154): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1154): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1154): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1154): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1154): EAPOL: enable timer tick
D/wpa_supplicant( 1154): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1154): htc_wext_set_keepalive +
I/wpa_supplicant( 1154): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1154): getPrivFuncNum +	
I/wpa_supplicant( 1154): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1154): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1154): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
I/wpa_supplicant( 1154): State: ASSOCIATED -> 4WAY_HANDSHAKE,
D/wpa_supplicant( 1154): Get randomness: len=32 entropy=6
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  905): Associated
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/Tethering(  905): interfaceStatusChanged wlan0, true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
I/wpa_supplicant( 1154): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7aa39f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1154):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1154): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1154): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ef2b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1154):    broadcast key
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1154): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1154): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1154): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1154): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1154): setConcurrentAPChannel: Set wifi.hotspot.channel to 1,
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1154): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1154): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1154): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1154): set send_ind_to_ndc = 0
I/wpa_supplicant( 1154): htc_wext_set_TX_TRACKING (1)+
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1154): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1154): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 1154): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1154): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1154): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1154): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1154): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1154): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1154): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 18
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1154): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1154): EAPOL authentication completed successfully
I/wpa_supplicant( 1154): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb,
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1154): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1154): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1154): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WISPrService( 3775): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3775): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1154): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1154): Power_Mode_Type mode = 1
I/wpa_supplicant( 1154): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(42524fe8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425a47b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425a47b0 target=com.android.internal.util.StateMachine$SmHandler }
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,W/dalvikvm( 4479): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4479): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4479): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4479): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4479): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=4195
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4195:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4195
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1322): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4508 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1322/10055)
,D/AutoSetting( 1322): Util - no network available!
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1322/10055)
D/AutoSetting( 1322): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1322): service - mHandler: cancel location update
D/AutoSetting( 1322): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4508): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4508): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4508): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4508): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4521 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4005
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4005:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4508/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4508/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4508/10079)
,W/fb4a(:<default>):UserScope( 4479): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4479): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4479): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4535 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4227
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4227:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4227
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4005
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4479): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4535): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4479): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4479): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
W/ContextImpl( 4535): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/dalvikvm( 4479): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4479): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4479): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4479): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4479): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4479): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4479): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4479): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4479): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4479): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4479): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4479): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4479): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4479): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/GAV2    ( 4535): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4535): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4535): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 9.913MB for 39954-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 9.987MB for 79892-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4535/10151)
,V/WebViewChromiumFactoryProvider( 4535): Binding Chromium to main looper Looper (main, tid 1) {41b15108}
,I/LibraryLoader( 4535): Expected native library version number "",actual native library version number ""
,I/chromium( 4535): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4535): Initializing chromium process, renderers=0
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 10.039MB for 84664-byte allocation
,D/PMS     (  905): acquireWL(440d8090): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,D/PMS     (  905): acquireWL(43d141a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,E/AudioManagerAndroid( 4535): BLUETOOTH permission is missing!
D/PMS     (  905): releaseWL(43d141a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4535): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4535): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4535): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4535): Local Branch: 
I/Adreno-EGL( 4535): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4535): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4535):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4535): Starting up...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4535/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4535/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3527/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3527/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,I/iu.Environment( 2177): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2177): num queued entries: 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,I/iu.UploadsManager( 2177): num updated entries: 0
,I/iu.SyncManager( 2177): NEXT; no task
,D/Process (  905): killProcessQuiet, pid=4258
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
I/ActivityManager(  905): Killing 4258:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
,I/ActivityManager(  905): Recipient 4258
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1154): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1154): EAPOL: disable timer tick
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 10.279MB for 75760-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4378f290 u0 ReceiverList{4378f170 4479 com.facebook.katana/10027/u0 remote:435098a8}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4378f290 u0 ReceiverList{4378f170 4479 com.facebook.katana/10027/u0 remote:435098a8}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{435ee650 u0 ReceiverList{435ee5f0 4479 com.facebook.katana/10027/u0 remote:435e6370}}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/PMS     (  905): acquireWL(43ca34e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43ca34e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4479): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4479): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422ce0b0
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422ce0b0, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e87bb8
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@4269d0c0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  905): mWirelessDisplayManager is null
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 315ms
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
,I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1251): ScreenObserver: OFF
,D/NfcService( 1251): applyRouting - 0
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4407
D/NfcService( 1251): applyRouting -2
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@431e1620)
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/PMS     (  905): acquireWL(43127de8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/PMN     (  905): wakingUp
D/PMS     (  905): releaseWL(43127de8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  905): No lock screen! windowToken=null
,D/PMN     (  905): onScreenOn
,D/PMS     (  905): acquireWL(441f1c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(441f1c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/MtpService( 2364): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2364): [MTP][onReceive]-
D/NfcService( 1251): applyRouting - 0
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1251): applyRouting -2
,D/AutoSetting( 1322): receiver - intent: android.intent.action.USER_PRESENT
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): acquireWL(43933ef8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  905): releaseWL(43933ef8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/TetherSettings( 3775): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3775): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3775): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3775): Cust_ConnectToPC   : spcsc>false
D/        ( 3775): Cust_ConnectToPC   : IPT>true
D/        ( 3775): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3775): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3775): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3775): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3775): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1322): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3775): onReceive:android.intent.action.USER_PRESENT
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,I/ClockThread( 1114): stop update clock
I/SmartNS_PSService( 3775): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1154): SET_SCREEN_ON:On
I/wpa_supplicant( 1154): htc_wext_set_keepalive +
I/wpa_supplicant( 1154): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1154): getPrivFuncNum +	
I/wpa_supplicant( 1154): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1154): htc_wext_set_keepalive fnum = 0x8bf6
W/Settings( 3775): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/wpa_supplicant( 1154): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1154): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1154): htc_wext_set_TX_TRACKING - ret = 0
I/SmartNS_PSService( 3775):  defaultType:0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1154): Change stage from stage0 to stage3
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  369): ParamSet string: screen_state=on
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1154): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  905): updateScreenOn: false
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4609 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1154): Power_Mode_Type mode = 0
I/wpa_supplicant( 1154): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  905): releaseWL(42524fe8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1154): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1154): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1154): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20732 delay=15s
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/PMS     (  905): acquireWL(43bc6a28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43bc6a28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
W/ContextImpl( 4609): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): acquireWL(4417a240): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WISPrService( 3775): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/WifiWatchdogStateMachine(  905): WAN detection
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1770): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1770): onScreenOn: 1452274449312
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1770): onScreenOn: 1452274449313
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/PMS     (  905): releaseWL(4417a240): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1114): WifiActivity: 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@42498f98
,D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/SmartSyncUtils( 4609): isEpsOn(), nState = 0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/PMS     (  905): acquireWL(4416f610): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4609 1000 null
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e87bb8
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e87bb8, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@4269d0c0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/PMN     (  905): goingToSleep
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/PMS     (  905): acquireWL(426e6ae8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:2
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(4362d990): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/PMS     (  905): releaseWL(4416f610): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4508/10079)
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20732 mDataStallAlarmIntent=PendingIntent{437d90f0: PendingIntentRecord{425d2a80 android broadcastIntent}}
I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
,I/logwrapper(  362): /system/bin/ip terminated by exit(254)
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/PMS     (  905): acquireWL(434130c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1154): SET_SCREEN_ON:Off
I/wpa_supplicant( 1154): htc_wext_set_keepalive +
I/wpa_supplicant( 1154): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1154): getPrivFuncNum +	
I/wpa_supplicant( 1154): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1154): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1154): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1154): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1154): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
V/SRS_Proc(  369): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4609): getMobilePolicyEnabled, result = true
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Killing 4281:com.htc.backup/1000 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=4281
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
I/ActivityManager(  905): Recipient 4281
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  905):    returned true
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,D/SmartSyncUtils( 4609): isEpsOn(), nState = 0
D/PMS     (  905): releaseWL(434130c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,W/ContextImpl( 4609): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4609): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4609): getMobilePolicyEnabled, result = true
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4269d0c0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4269d0c0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4269d0c0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:,
D/WifiService(  905): New client listening to asynchronous messages
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI,
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4269d0c0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426bf7d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426bf7d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/PMS     (  905): releaseWL(4362d990): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/NetworkPolicy(  905): updateScreenOn: false
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1322): service - mHandler: cancel location update
,D/AutoSetting( 1322): service -           changes count: 0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] getTotalRam: 1873 Mb
D/PMS     (  905): acquireWL(436dbdc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(436dbdc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(44147470): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1770): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1770): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1770): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1770): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1770): onScreenOff
D/PMS     (  905): releaseWL(44147470): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(431fd838): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43666ed0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2177): Checkin interval check for package: unspecified last checkin: 1452274398537 min interval config: 0 actual interval: 50951
I/CheckinService( 2177): Checking schedule, now: 1452274449492 next: 1452274428507
,I/CheckinService( 2177): active receiver: enabled
D/PMS     (  905): releaseWL(431fd838): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2177, uid=10029, userID:0
,I/CheckinService( 2177): Preparing to send checkin request
,I/EventLogService( 2177): Accumulating logs since 1452274394892
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,I/CheckinRequestBuilder( 2177): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2177): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2177/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4644 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4644): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4644): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4644): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4644): install
,I/MultiDex( 4644): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4644): loading existing secondary dex files
,I/MultiDex( 4644): load found 3 secondary dex files
,I/MultiDex( 4644): install done
,W/dalvikvm( 4644): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4644): VFY: unable to resolve instance field 36
,W/dalvikvm( 4644): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4644): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4644): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{42311b70 u0 com.test.thalitest/.MainActivity t2}
,W/dalvikvm( 4644): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4644): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1219): callingUid 10029, callindPid: 1219
,W/dalvikvm( 4644): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4644): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4644): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4644): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4644): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/MDM     ( 1219): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2177): Restart initialization of location
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
D/PMS     (  905): acquireWL(44185658): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(44185658): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/AuthorizationBluetoothService( 1350): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1350): Proximity feature is not enabled.
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4644): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  369): PrepareKeyRequest: nonce=141901336
,I/WVCdm   (  369): CdmEngine::CloseSession
,D/PMS     (  905): releaseWL(4258f558): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): acquireWL(440995a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
,D/PMS     (  905): releaseWL(440995a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,I/NetworkMonitor( 4459): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4459/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4508/10079)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10076)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3865/10053)
D/AccTypeManager( 1339): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): CONNECTED
V/Tethering(  905): bSetPropertyMultiRAB:false
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  905): Found interface wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
D/PMS     (  905): acquireWL(430eae70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
D/PMS     (  905): releaseWL(430eae70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1339): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1339): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42311ad8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2364/10021)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
D/PMS     (  905): releaseWL(42311ad8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!,
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1339): Unsupported attribute readOnly
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,D/AutoSetting( 1322): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1322/10055)
,D/MobileConnectivityChangeReceiver( 4508): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4508): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1322): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1322): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1322): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1322): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1322/10055)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4535/10151)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3527/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3527/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4644/10029)
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2177): Checkin interval check for package: unspecified last checkin: 1452274398537 min interval config: 0 actual interval: 51933
D/PMS     (  905): acquireWL(429a1c10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(429a1c10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2177, uid=10029, userID:0
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2177): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2177): num queued entries: 0
,I/iu.UploadsManager( 2177): num updated entries: 0
,I/iu.SyncManager( 2177): NEXT; no task
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
,D/PMS     (  905): acquireWL(425d1890): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/libc    ( 1350): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1350): [NET] getaddrinfo-,err=8
D/libc    ( 1350): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1350): [NET] getaddrinfo-, 1
D/libc    ( 1350): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =ab86 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 260
D/libc    (  362): [NET]res_nsend:resplen=79
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1350): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/libc    ( 1350): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1350): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,W/fb4a(:<default>):UserScope( 4479): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4479): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    ( 1350): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1350): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,W/Settings( 4644): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
D/PMS     (  905): acquireWL(426bf580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/PMS     (  905): releaseWL(425d1890): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1350/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/PMS     (  905): releaseWL(426bf580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(425d3fb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1350/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1350/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
D/PMS     (  905): releaseWL(425d3fb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,E/fb4a(:<default>):LocalFbBroadcastManager( 4479): Called registerBroadcastReceiver twice.
,D/WVCdm   (  369): PrepareKeyRequest: nonce=2683163911
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,I/WVCdm   (  369): CdmEngine::CloseSession
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4479/10027)
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2177): Classify the device as Phone.
,D/libc    ( 2177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2177): [NET] getaddrinfo-,err=8
D/libc    ( 2177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2177): [NET] getaddrinfo-, 1
,D/libc    ( 2177): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =3192 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 157
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2177): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 2177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2177): [NET] getaddrinfo-,err=8
,D/PMS     (  905): releaseWL(440d8090): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  905): acquireWL(437e38a8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4459 10154 null
,W/ContextImpl( 4459): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4459, uid=10154, userID:0
I/MusicLeanback( 4459): Conditions not met for autocaching.
,I/MusicLeanback( 4459): Stop autocaching.
D/libc    ( 2177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2177): [NET] getaddrinfo-,err=8
,D/PMS     (  905): releaseWL(437e38a8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
D/libc    ( 2177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2177): [NET] getaddrinfo-,err=8
W/ContextImpl( 4459): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [12][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
I/CheckinTask( 2177): Sending checkin request (12204 bytes)
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,I/CheckinRequestBuilder( 2177): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2177): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2177/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=14 [14][2][0]
,I/CheckinRequestBuilder( 2177): Classify the device as Phone.
,I/CheckinTask( 2177): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2177): Checking schedule, now: 1452274451898 next: 1452797388894
,I/CheckinService( 2177): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2177, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,I/CheckinService( 2177): Checking schedule, now: 1452274451922 next: 1452797388894
,I/CheckinService( 2177): active receiver: disabled
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2177, uid=10029, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
,D/CheckinService( 2177): Recording last checkin time for package unspecified as 1452274451927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/PMS     (  905): releaseWL(43666ed0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,D/GCM     ( 1350): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =eb2e +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE,
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success,
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175,
,I/GAV2    ( 4535): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4407): Test app app.js loaded
I/jxcore-log( 4407): 
,I/Choreographer( 4407): Skipped 526 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4407): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4407): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b1d130 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4407): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  905): releaseWL(426e6ae8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AutoSetting( 1518): service - handleMessage() stop self
,D/AutoSetting( 1518): service - onDestroy() END
,D/AutoSetting( 1518): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4299
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  905): killProcessQuiet, pid=4245
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4299:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  905): Killing 4245:com.htc.cs.dm/u0a98 (adj 15): empty #18
,I/ActivityManager(  905): Recipient 4299
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4245
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1339): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4697 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1268): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/Launcher( 1268): Deferring update until onResume
,D/Launcher( 1268): waitUntilResume // bindAppsUpdated
,W/AccTypeManager( 1339): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1339): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1339): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4697): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4697): MmsConfig.loadMmsSettings
,W/dalvikvm( 4697): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4697): VFY: unable to resolve instance field 36
,W/dalvikvm( 4697): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4697): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4720 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4697, uid=10111, userID:0
,D/MessageFrequencyProvider( 4720): onCreate
,W/Settings( 4697): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 4720): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4720): GetPrviateResource
,V/GetPrviateResource( 4720): GetPrviateResource
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4697, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4697, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4697, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4697, uid=10111, userID:0
,D/MmsCustomizationProvider( 4720): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4697, uid=10111, userID:0
,I/Babel   ( 4697): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4697): MmsConfig.loadFromDatabase
D/PMS     (  905): acquireWL(426b6000): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4697 10111 null
,I/ProviderInstaller( 4697): Installed default security provider GmsCore_OpenSSL
,E/Babel   ( 4697): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4697): MmsConfig.loadFromResources
,E/Babel   ( 4697): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4697): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/[PluginManager]RegisterService( 1322): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1322): handle notify Blinkfeed plugin client changed
,D/Process (  905): killProcessQuiet, pid=3865
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  905): Killing 3865:com.htc.musicenhancer/u0a53 (adj 15): empty #17
I/IcingCorporaProvider( 2828): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/MessageCustFlag( 4720): sense_version=6.0
,D/BTAccessoryUtil( 4720): createReceiver
,D/BTAccessoryUtil( 4720): registerReceiver return intent = null
D/MessageCustFlag( 4720): sku_id=99
,W/SystemReader( 4720): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  905): acquireWL(43be5bf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3527 10160 null
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  905): acquireWL(440925b8): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
D/Messaging( 4720): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4720): networkCode: 
D/MessageCustFlag( 4720): sku_id=99
D/MmsConfig( 4720): SIE smsPri: null
,D/MmsConfig( 4720): networkCode: 
D/PMS     (  905): releaseWL(43be5bf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/HtcTelephonyCapability( 4720): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4720): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4720): getRATByHtcTelephonyCapability:1
,D/PMS     (  905): releaseWL(440925b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/SystemReader( 4720): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  905): acquireWL(426ce228): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426b6000): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Recipient 3865
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 2177): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2177): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 2177): updateResources: need to parse f{com.google.android.gms}
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/PackageManager(  905): Unable to load service info ResolveInfo{43b61418 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/IcingCorporaProvider( 2828): UpdateCorporaTask done [took 906 ms] updated apps [took 906 ms] 
,I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1268): loadItems() com.htc.launcher.pageview.WidgetManager@41ba5c70 +
,I/Prism.WidgetManager( 1268): onLoadItems() +
,I/Icing   ( 2177): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2177): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(426ce228): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1268): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1268): onLoadItems() -
,I/Prism.ItemManager( 1268): loadItems() com.htc.launcher.pageview.WidgetManager@41ba5c70 -
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/GCoreNlp( 1219): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1241): -- N1 =0
,D/PhoneApp( 1241): -- N2 =0
,D/PhoneApp( 1241): -- N3 =0
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(43d360a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43d360a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
,D/PMS     (  905): acquireWL(42656cc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42656cc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4360a420): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4360a420): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c10ba0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43c10ba0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4720): mNeedToUpdateDate2 start
,D/MmsConfig( 4720): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4720): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4720): 
D/MmsAsyncWorkHandler( 4720): HM tk = 20001
D/ReportIndicatorCache( 4720): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4720): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b22460
,I/Messaging( 4720): mccmnc> 
D/DraftCache( 4720): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4720): [DraftCache/1] refresh
D/MmsConfig( 4720): networkCode: 
,D/Messaging( 4720): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/PhoneStorageUtil( 4720): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4720): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4720): createReceiver
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4720): sense_version=6.0
,D/Jerry   ( 4720): start to preload cursor >>>>>>>
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1241): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,V/MmsProvider( 1241): Update uri=content://mms, match=0
,V/MmsProvider( 1241): selection=st=129 AND m_type!=134
,D/Messaging( 4720): mNeedToUpdateDate2: false
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
,D/AccFlag ( 1241): sku_id=99
,D/Messaging( 4720): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4720): TransactionService is going to be woken up.
,V/TransactionService( 4720): 1-Creating TransactionService
,D/DraftCache( 4720): [DraftCache/472] rebuildCache
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,V/TransactionService( 4720): onStartCommand: 1
D/MmsSystemEventReceiver( 4720): unRegisterForConnectionStateChanges
V/TransactionService( 4720): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4720): Loading previous transactions.
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4720): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/Messaging( 4720): ViewCache CreatePreload
,D/Messaging( 4720): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Jerry   ( 1241): URI_DRAFT
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): device_type: 1
,D/Cust_MMSMS( 4720): _has_set_default_values_2=true
,D/DraftCache( 4720): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4720): [DraftCache/472] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4720): 
D/MmsAsyncWorkHandler( 4720): HM tk = 20002
,D/TransactionService( 4720): Force set service start id to 1
,V/TransactionService( 4720): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4720): unRegisterForConnectionStateChanges
,D/MsgPreferenceUtils( 4720): def_index: 0
,V/TransactionService( 4720): Destroying TransactionService
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
D/TransactionService( 4720): stopSelfResult: true, mLastHandledServiceId: 1
,D/AccFlag ( 1241): sku_id=99
,V/TransactionService( 4720): 4-Handling incoming message: { when=-14ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): sku_id=99
,D/MsgPreferenceUtils( 4720): globalIndex = 1
,D/MsgPreferenceUtils( 4720): phone state: true
D/MsgPreferenceUtils( 4720): sd state: false
,D/MsgPreferenceUtils( 4720): vIndex = 0
,D/PMS     (  905): acquireWL(44247f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{439290e0: PendingIntentRecord{427a61a8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=119806, Int=0
,D/PMS     (  905): releaseWL(44247f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(441ba6a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=7 [13][1][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(4417a098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4417a098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(441ba6a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44136b88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/PMS     (  905): releaseWL(44136b88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4410c970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(440d5710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(440b8d30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1219): Vacuum at: now=1452274464437 tag=VacuumService
D/PMS     (  905): releaseWL(4410c970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(440d5710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4408ccf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/PMS     (  905): releaseWL(4408ccf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43ba06c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
D/PMS     (  905): releaseWL(440b8d30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43ba06c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42646548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/PMS     (  905): releaseWL(42646548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(423bc500): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(423bc500): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(424c4510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42521728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42521728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42594718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(424c4510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42480a80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/PMS     (  905): releaseWL(42480a80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1219): Scheduling Phenotype for one-off execution 11611 seconds from now (1452274464971)
,D/GetConfigurationSnapshotOperation( 1219): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1219): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1219): Using platform SSLCertificateSocketFactory
,I/GAV4    ( 4697): Thread[GAThread,5,main]: No campaign data found.
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1219): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1219): [NET] getaddrinfo-, 1
,D/libc    ( 1219): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =a3e5 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 290
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1219): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [12][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
,D/Process (  905): killProcessQuiet, pid=4329
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4329:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4329
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(42594718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425bda60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/PMS     (  905): releaseWL(425bda60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4255d920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1154): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1154): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1154): nl80211: survey data missing!
E/wpa_supplicant( 1154): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1154): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/PMS     (  905): releaseWL(4255d920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(43c3c4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/PMS     (  905): releaseWL(43c3c4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42502f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{422526c0: PendingIntentRecord{426b8d30 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135041, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1350/10029)
,D/PMS     (  905): releaseWL(42502f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1322): service - mHandler: update timezone
,D/AutoSetting( 1518): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1518): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1518): service - onCreate()
,D/AutoSetting( 1322): service - handleMessage() stop self
,D/AutoSetting( 1518): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1518): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1572): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1518): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1518): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1518): service - mHandler: update timezone
D/AutoSetting( 1322): service - handleMessage() quit looper
D/AutoSetting( 1322): service - onDestroy() END
,D/AutoSetting( 1518): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1518): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1518): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1518): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1114): removeNotification.gc:55
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41f49e10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 3 9 3 11
,D/PMS     (  905): acquireWL(425c3260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{424d4098: PendingIntentRecord{424cd320 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142250, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(42747318): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(425c3260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =292 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=238
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  905): killProcessQuiet, pid=4344
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4344:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4344
,D/PMS     (  905): releaseWL(42747318): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{423cfab8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  905): acquireWL(42492d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{421a5888: PendingIntentRecord{41f1f040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=155574, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42492d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4409b1a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/PMS     (  905): releaseWL(4409b1a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1518): service - handleMessage() stop self
,D/AutoSetting( 1518): service - onDestroy() END
,D/AutoSetting( 1518): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=3976
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3976:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3976
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(437cfec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(437cfec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(426a4c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{421a5888: PendingIntentRecord{41f1f040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=215574, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(426a4c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42609dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{42445dd8: PendingIntentRecord{43805030 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=223881, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4806 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{42604f98: PendingIntentRecord{42752708 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452274556532, Int=10800000
,D/PMS     (  905): releaseWL(42609dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4806/10049)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/Process (  905): killProcessQuiet, pid=4377
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4377:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4377
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(440d3a98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(440d3a98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4269b910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{440b3528: PendingIntentRecord{436cd520 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=224633, Int=120000
,V/AlarmManager(  905): sending alarm PendingIntent{432134c8: PendingIntentRecord{43805030 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=224919, Int=0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025079
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025270
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026706
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026743
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029485
,D/PMS     (  905): releaseWL(4269b910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4266c098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/PMS     (  905): releaseWL(4266c098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(436d7440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{421a5888: PendingIntentRecord{41f1f040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=275574, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(436d7440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(44140b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44140b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4407): ****TEST TOOK:  ms ****
I/jxcore-log( 4407): 
,I/jxcore-log( 4407): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4407): 
,E/cutils-trace( 4832): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4832): ====startRecUseTime====
D/htc.customization.log.level( 4832):  is 
,W/CustomizationLogLevel( 4832): Level value is invalid, use default level 2
,D/CustomizationManager( 4832):  Read ACC file spent 0.074 (s)
D/CIDMapFileReader( 4832): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4832): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4832): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4832): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4832): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4832): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4832): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4832): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4832): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4832): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4832): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4832): Parsing tag category name = system
I/CustomizationCIDLoader( 4832): Parsing tag category name = application
I/CustomizationCIDLoader( 4832): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 4832): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4832): Parsing tag category name = AudioService,
I/CustomizationCIDLoader( 4832): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4832): Parsing tag category name = Settings
D/CustomizationManager( 4832):  Read CID file spent 0.123 (s)
,D/CustomizationManager( 4832):  All configurations done spent 0.123 (s)
W/HtcNativeFlag( 4832): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4832): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4832): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4832): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4832, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,I/ActivityManager(  905): Killing 4407:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
D/Process (  905): killProcessQuiet, pid=4407
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905):   Force finishing activity ActivityRecord{42311b70 u0 com.test.thalitest/.MainActivity t2}
,W/PackageSettings(  905): Skipping PackageSetting{41fb1900 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  905): WIN DEATH: Window{425c3898 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  905): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
,D/AccTypeManager( 1339): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): acquireWL(431f05d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(431f05d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/VoicemailCleanupService( 1298): Cleaning up data for package: com.test.thalitest
,W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4407 uid 10389
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1339): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,D/AccTypeManager( 1339): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/Binder  ( 1207): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1207): java.lang.NullPointerException
W/Binder  ( 1207): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1207): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1207): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1207): 	at dalvik.system.NativeStart.run(Native Method)
,I/PackageManager(  905):   Scheme: "smsto"
,I/[PluginManager]RegisterService( 1322): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/[PluginManager]RegisterService( 1322): handle notify Blinkfeed plugin client changed
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
,I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1339): Unsupported attribute readOnly
,I/Launcher( 1268): Deferring update until onResume
D/Launcher( 1268): waitUntilResume // bindAppsRemoved
,D/Prism.PackageStateRece_( 1268): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
,I/IcingCorporaProvider( 2828): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4847 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  905): acquireWL(424c4a80): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2828): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
,W/PackageManager(  905): Unable to load service info ResolveInfo{425b5dc8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,E/SQLiteDatabase( 4847): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4847): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4847): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4847): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4847): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4847): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4847): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4847): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4847): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4847): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4847): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4847): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4847): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4847): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4847): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4847): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4847): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4847): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4847): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/SQLiteDatabase( 4847): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4847): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4847): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4847): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4847): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4847): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4847): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4847): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4847): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4847): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4847): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4847): 	at Bw.a(ClientFlagsModule.java:32),
E/SQLiteOpenHelper( 4847): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4847): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4847): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4847): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4847),: 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4847): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4847): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4847): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4847): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4847): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4847): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4847): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4847): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4847): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4847): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4847): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4847): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4847): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4847): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4847): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4847): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4847): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4847): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4847): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4847): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4847): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4847): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4847): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4847): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4847): threadid=11: thread exiting with uncaught exception (group=0x416e2e30)
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/AndroidRuntime( 4847): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4847): Process: com.google.android.apps.docs, PID: 4847
E/AndroidRuntime( 4847): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4847): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4847): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4847): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4847): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4847): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4847): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4847): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
,E/DropBoxManagerService(  905): Can't write: system_app_crash
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
,E/SQLiteDatabase( 4847): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4847): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4847): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4847): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4847): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4847): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4847): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4847): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4847): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4847): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4847): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4847): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4847): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4847): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4847): killProcess, pid=4847
E/SQLiteOpenHelper( 4847): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4847): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4847): 	at a,ndroid.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4847): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4847): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4847): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4847): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4847): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4847): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4847): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4847): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4847): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4847): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4847): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4847): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4847): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4847): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4865 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4847
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4847) has died.
,W/ContextImpl( 4865): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4865): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
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
E/SQLiteDatabase( 4865): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4865): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4865): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4865): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4865): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4865): threadid=10: thread exiting with uncaught exception (group=0x416e2e30)
E/AndroidRuntime( 4865): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4865): Process: com.android.keychain, PID: 4865
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
E/AndroidRuntime( 4865): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4865): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4865): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4865): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4865): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4878 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4865): killProcess, pid=4865
,D/Process ( 4865): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452274653340.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  905): Recipient 4865
,I/ActivityManager(  905): Process com.android.keychain (pid 4865) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AppTag  ( 4878): getInstance(Context context)
,D/AppTag  ( 4878): getInstance(Context context)
,D/AppTag  ( 4878): onCreate()
,D/PMS     (  905): acquireWL(42534868): PARTIAL_WAKE_LOCK  AsyncService 0x1 3527 10160 null
,D/PMS     (  905): releaseWL(42534868): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4055): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/PackageBroadcastService( 2177): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2177): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2177): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2177): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 2177): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2177): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 2177): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2177): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66be9aa8
,W/dalvikvm( 2177): threadid=43: thread exiting with uncaught exception (group=0x416e2e30)
E/SQLiteLog( 2177): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2177): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6563c9d8
,E/DriveAsyncService( 2177): disk I/O error (code 3850)
E/DriveAsyncService( 2177): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2177): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2177): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2177): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2177): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2177): 	at java.lang.Thread.run(Thread.java:864)
,I/LocationSettingsChecker( 2177): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager(  905): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2177): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2177): Process: com.google.android.gms, PID: 2177
E/AndroidRuntime( 2177): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2177): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2177): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2177): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2177): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2177): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2177): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2177): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2177): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2177): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2177): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2177): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2177): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 2177): killProcess, pid=2177
,D/Process ( 2177): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  905): Recipient 2177
,I/ActivityManager(  905): Process com.google.android.gms (pid 2177) has died.
D/PMS     (  905): handleWLDeath(424c4a80): PARTIAL_WAKE_LOCK  Icing 0x1
,D/WifiService(  905): Client connection lost with reason: 4
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 21000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 31000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30999ms
,I/ActivityManager(  905): Resuming delayed broadcast
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30997ms
,E/SQLiteLog( 1350): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1350): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x640226e8
,W/dalvikvm( 1350): threadid=1: thread exiting with uncaught exception (group=0x416e2e30)
,E/AndroidRuntime( 1350): FATAL EXCEPTION: main
E/AndroidRuntime( 1350): Process: com.google.process.gapps, PID: 1350
E/AndroidRuntime( 1350): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1350): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1350): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1350): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1350): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1350): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1350): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1350): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1350): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1350): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1350): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1350): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1350): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1350): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1350): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1350): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1350): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1350): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1350): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1350): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1350): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1350): 	... 10 more
,E/ActivityManager(  905): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 1350): killProcess, pid=1350
,D/Process ( 1350): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4908 uid=10098 gids={50098, 3003, 5012}
,I/ActivityManager(  905): Recipient 1350
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.process.gapps (pid 1350) has died.
,D/WifiService(  905): Client connection lost with reason: 4
,I/DeviceManagement( 4908): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4908 dbg=false s=true
,I/DeviceManagement( 4908): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30877ms
I/DeviceManagement( 4908): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4908): WorkflowService: Starting workflow service
I/DeviceManagement( 4908): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b41f20] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4908): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4908): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4908): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4908): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4922 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4908): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4908): SessionStateController: Checking invariants...
,D/Documents( 4922): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4922): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4922): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4922): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4922): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4922): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4922): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4922): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4922): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4922): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4922): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4922): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4922): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4922): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4922): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4922): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4922): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4922): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4922): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4922): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4922): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4922): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4922): threadid=1: thread exiting with uncaught exception (group=0x416e2e30)
E/AndroidRuntime( 4922): FATAL EXCEPTION: main
E/AndroidRuntime( 4922): Process: com.android.documentsui, PID: 4922
E/AndroidRuntime( 4922): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4922): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4922): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4922): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4922): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4922): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4922): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4922): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4922): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4922): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4922): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4922): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4922): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4922): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4922): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4922): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4922): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4922): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4922): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4922): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4922): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4922): 	... 10 more
,I/ActivityManager(  905): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4936 uid=10023 gids={50023, 1028, 1015, 1023}
,I/ActivityManager(  905): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4948 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/Process (  905): killProcessQuiet, pid=4609
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/ActivityManager(  905): App crashed! Process: com.android.documentsui
I/ActivityManager(  905): Killing 4609:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process (  905): killProcessQuiet, pid=4508
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  905): Killing 4508:com.google.android.setupwizard/u0a79 (adj 15): empty #17
I/ActivityManager(  905): Recipient 4609
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452274653852.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  905): Recipient 4508
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process ( 4922): killProcess, pid=4922
,D/Process ( 4922): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/ExternalStorage( 4936): After updating volumes, found 1 active roots
I/ActivityManager(  905): Recipient 4922
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.documentsui (pid 4922) has died.
,E/SQLiteDatabase( 4908): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4908): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4908): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4908): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4908): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4908): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4908): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4908): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4908): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4908): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4908): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4908): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4908): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4908): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4908): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 4948): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
I/DeviceManagement( 4908): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4908): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4908): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
W/dalvikvm( 4948): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4948): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4948): install
E/SQLiteDatabase( 4908): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4908): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4908): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4908): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4908): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4908): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4908): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4908): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4908): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4948): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
W/DeviceManagement( 4908): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b41f20]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4908): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4908): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4908): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4908): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4908): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4908): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4908): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4908): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4908): WorkflowService: Stopping workflow service
I/MultiDex( 4948): loading existing secondary dex files
I/MultiDex( 4948): load found 3 secondary dex files
I/MultiDex( 4948): install done
,I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1268): loadItems() com.htc.launcher.pageview.WidgetManager@41ba5c70 +
,I/Prism.WidgetManager( 1268): onLoadItems() +
I/ActivityManager(  905): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=4965 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}

```
