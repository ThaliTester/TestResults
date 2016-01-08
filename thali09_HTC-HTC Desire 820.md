#### Test 549702619369e5e_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  905): setLight #0: color=#26
V/LightsService(  905): setLight #0: color=#23
,V/LightsService(  905): setLight #0: color=#1c
V/LightsService(  905): setLight #0: color=#14
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 19
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/PMS     (  905): acquireWL(42d03aa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
V/AlarmManager(  905): sending alarm PendingIntent{44836878: PendingIntentRecord{42e7e048 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452292035010, Int=0
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4442 uid=10078 gids={50078}
V/AlarmManager(  905): sending alarm PendingIntent{42d1bc60: PendingIntentRecord{42cc88b0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452292041206, Int=60000
D/PMS     (  905): releaseWL(42d03aa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
D/SMSBackup( 4442): SMSBackupAgentService started
D/SMSBackup( 4442): Checking restore status
D/SMSBackup( 4442): Restore complete
D/SMSBackup( 4442): cancelCheckAlarm
D/SMSBackup( 4442): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
E/cutils-trace( 4440): Error opening trace file: No such file or directory (2)
D/Finsky  ( 4149): [434] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4149): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  905): killProcessQuiet, pid=3485
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3485:com.htc.task/u0a71 (adj 15): empty #17
D/CustomizationManager( 4440): ====startRecUseTime====
D/htc.customization.log.level( 4440):  is 
W/CustomizationLogLevel( 4440): Level value is invalid, use default level 2
I/ActivityManager(  905): Recipient 3485
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 4440):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4440): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4440): Parsing tag category name = system
I/CustomizationCIDLoader( 4440): Parsing tag category name = application
I/CustomizationCIDLoader( 4440): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4440): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4440): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4440): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4440): Parsing tag category name = Settings
D/CustomizationManager( 4440):  Read CID file spent 0.105 (s)
D/CustomizationManager( 4440):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 4440): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4440): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4440): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4440): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4440
D/PMS     (  905): acquireHCC(42ad3508): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(42d19fb0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x6c27cf08 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1137887424
I/FeedHostManager( 1276): [onPause]
I/FeedProviderManager( 1276): onPause
I/FeedHostManager( 1276): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42348858
I/SocialFeedProvider( 1276): +onPause
I/SocialFeedProvider( 1276): -onPause
D/PMS     (  905): acquireWL(438dd840): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4464 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1276): [trimMemory] 20
W/asset   ( 4464): Copying FileAsset 0x5c769648 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4464): Binding Chromium to main looper Looper (main, tid 1) {42259980}
I/LibraryLoader( 4464): Expected native library version number "",actual native library version number ""
I/chromium( 4464): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4464): Initializing chromium process, renderers=0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43a0e740:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  905): acquireWL(43d1be70): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): acquireWL(42d85d50): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): releaseWL(43d1be70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4464): 1109871696: getState(). Returning 12
I/Adreno-EGL( 4464): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4464): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4464): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4464): Local Branch: 
I/Adreno-EGL( 4464): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4464): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4464):                  aa63bbd948f41d15fc72f585e
W/chromium( 4464): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/ActivityManager(  905): Waited long enough for: ServiceRecord{42e02fa8 u0 com.htc.htclocationservice/.AutoSettingService}
W/dalvikvm( 4464): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4464): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4464): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4464): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4464): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4464): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4464): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4464): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4464): CordovaWebView is running on device made by: HTC
,W/AwContents( 4464): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  905): Disable input method client, pid=1276
I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +267ms
I/InputMethodManagerService(  905): Enable input method client, pid=4464
W/ResourceType( 4464): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4464): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@422a6300, mServedView=org.apache.cordova.engine.SystemWebView{4226bf68 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 4464): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  905): releaseWL(438dd840): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4464): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4464): JniHelper::setJavaVM(0x41e1f010), pthread_self() = 1662536312
D/JX-Cordova( 4464): jxcore cordova android initializing
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 11.587MB for 95956-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 11.667MB for 143930-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 11.783MB for 215890-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 11.951MB for 323830-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 12.223MB for 485740-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 13.233MB for 1092904-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 14.134MB for 1639352-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 15.466MB for 2459024-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(42ad3508): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(42d19fb0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 17.581MB for 3688532-byte allocation
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 38
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,W/jxcore-log( 4464): Initializing JXcore engine
,W/jxcore-log( 4464): JXcore engine is ready
,W/jxcore-log( 4464): Starting JXcore engine
,W/jxcore-log( 4464): Platform android
W/jxcore-log( 4464): 
,W/jxcore-log( 4464): Process ARCH arm
W/jxcore-log( 4464): 
,D/PMS     (  905): releaseWL(42d85d50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4464): JXcore Cordova bridge is ready!
I/jxcore-log( 4464): 
,W/jxcore-log( 4464): JXcore engine is started
,I/chromium( 4464): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4464): Toggling radios to true
I/jxcore-log( 4464): 
,D/BluetoothAdapter( 4464): enable(): BT is already enabled..!
,D/WifiManager( 4464): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1100
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
,W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
D/WifiManager( 4464): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4464): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): TDLS: Tear down peers
,I/wpa_supplicant( 1160): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4464): Radios toggled
I/jxcore-log( 4464): 
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4464, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1160): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1160): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1160): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1160): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb77b4bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1160):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1160): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1160): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1160): Wireless e,vent: cmd=0x8b15 len=20
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1160): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
,D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(4444c460): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  905): [RunningState] Stop DHCP
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): Fast associate: Old scan results
I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
,D/WifiNative-wlan0(  905):    returned true
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20087 mDataStallAlarmIntent=PendingIntent{42d380e0: PendingIntentRecord{42c13818 android broadcastIntent}}
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): Provision feature enable=false
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  905): isAvailable+-
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/UsbnetStateTracker(  905): reconnect
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/UsbnetStateTracker(  905): isAvailable+-
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WISPrService( 4133): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  905): New client listening to asynchronous messages
,D/WISPrService( 4133): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4133): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 4133): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1348): Read error: ssl=0x660e6558: I/O error during system call, Connection timed out
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/libc    (  363): [NET] entry_id:3   entry:0xb8949220  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb8949738  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8948fd8  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb89492f8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8949428  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb8949860  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb89490e8  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb8948d90  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,V/NativeCrypto( 1348): SSL shutdown failed: ssl=0x660e6558: I/O error during system call, Broken pipe
D/PMS     (  905): acquireWL(43a5c8e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  905): acquireWL(441466f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1160): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  905):    returned false
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1348/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  905): releaseWL(43a5c8e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,D/PMS     (  905): releaseWL(441466f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  905): NoActiveNetworkState
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3884/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1571/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4316/10100)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/PMS     (  905): acquireWL(43d31018): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
,I/NetworkMonitor( 3884): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): DISCONNECTED
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4316/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1967/10021)
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4517 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/PMS     (  905): releaseWL(43d31018): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4517): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4517): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4517): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4517): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4517): Preparing secondary program dexes.
V/DexLibLoader( 4517): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4517): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4517): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4517): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4517): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4517): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4517): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4517): Dex already copied
D/OdexVerifier( 4517): Odex verification is skipped.
,V/DexLibLoader( 4517): Creating class loader
,V/DexLibLoader( 4517): Finished creating class loader
V/DexLibLoader( 4517): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4517): Dex already copied
D/OdexVerifier( 4517): Odex verification is skipped.
,V/DexLibLoader( 4517): Creating class loader,
V/DexLibLoader( 4517): Finished creating class loader
V/DexLibLoader( 4517): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4517): Dex already copied
D/OdexVerifier( 4517): Odex verification is skipped.
V/DexLibLoader( 4517): Creating class loader
V/DexLibLoader( 4517): Finished creating class loader
V/DexLibLoader( 4517): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4517): Dex already copied
D/OdexVerifier( 4517): Odex verification is skipped.
V/DexLibLoader( 4517): Creating class loader
V/DexLibLoader( 4517): Finished creating class loader
V/DexLibLoader( 4517): Verifying classes from secondary dexes.
D/DexLibLoader( 4517): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4517): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4517): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4517): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4517): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4517): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4517): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4517): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1160): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1160): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1160): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 3
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 1
I/wpa_supplicant( 1160): wpa_s->is_screen_on 1
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): selected network = 1
D/wpa_supplicant( 1160): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb77b64e8  current_ssid=0x0
D/wpa_supplicant( 1160): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1160): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1160): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1160): check if in concurrent case
I/wpa_supplicant( 1160): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
W/dalvikvm( 4517): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1160): RSN: PMKSA cache search - network_ctx=0xb77b64e8 try_opportunistic=0
D/wpa_supplicant( 1160): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1160): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1160): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1160): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1160): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1160): nl80211: Unsubscribe mgmt frames handle 0xb77b5718 (mode change)
D/wpa_supplicant( 1160): nl80211: Subscribe to mgmt frames with non-AP handle 0xb77b5718
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb77b5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb77b5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb77b5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb77b5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb77b5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb77b5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb77b5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb77b5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb77b5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb77b5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1160):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1160):   * freq=2412
D/wpa_supplicant( 1160):   * Auth Type 0
D/wpa_supplicant( 1160):   * WPA Versions 0x2
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1160): nl80211: Connect request send successfully
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I,/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (489) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-49
I/wpa_supplicant( 1160): tsf=0000000101771080
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-55
I/wpa_supplicant( 1160): tsf=0000000101771096
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000101771099
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=3
I/wpa_supplicant( 1160): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-55
I/wpa_supplicant( 1160): tsf=0000000101771091
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1160): ssid=01ABC
I/wpa_supplicant( 1160): ####
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 101771080, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 101771096, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 101771099, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 101771091, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/dalvikvm( 4517): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1160): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1160): nl80211: Connect event
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1160): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1160): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1160): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1160): TDLS: Remove peers on association
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1160): EAPOL: enable timer tick
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1160): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1160): Get randomness: len=32 entropy=5
,D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/Tethering(  905): interfaceStatusChanged wlan0, true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1160): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb77b59f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1160):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1160): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed8b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1160):    broadcast key
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1160): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1160): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1160): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1160): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1160): wlan0: Connect to SSID: NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1160): set send_ind_to_ndc = 0
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1160): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1160): EAPOL authentication completed successfully
I/wpa_supplicant( 1160): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  905): This record is existed, only update it...
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WISPrService( 4133): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4133): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [2][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 1
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
,E/FbInjectorInitializer( 4517): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(443d3720): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42cf5bb0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42cf5bb0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4517): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4517): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4517): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4517): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=4249
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4249:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4249
,D/AutoSetting( 1331): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4544 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1331/10055)
,D/AutoSetting( 1331): Util - no network available!
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1331/10055)
D/AutoSetting( 1331): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1331): service - mHandler: cancel location update
D/AutoSetting( 1331): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4544): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4544): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4544): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4544): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@429ab058
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@429ab058, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42a70b70
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@42daf648
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  905): Going to sleep due to screen timeout...
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,D/Process (  905): killProcessQuiet, pid=3862
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4558 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 3862:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4544/10079)
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
,W/PMS     (  905): mWirelessDisplayManager is null
,W/fb4a(:<default>):UserScope( 4517): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4544/10079)
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4517): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
I/ActivityManager(  905): Recipient 3862
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4544/10079)
,W/fb4a(:<default>):UserScope( 4517): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 314ms
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43a48030)
D/NfcService( 1262): ScreenObserver: OFF
,D/NfcService( 1262): applyRouting - 0
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4464
D/PMN     (  905): wakingUp
,D/NfcService( 1262): applyRouting -2
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  905): acquireWL(44462d70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
D/PMS     (  905): releaseWL(44462d70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  905): No lock screen! windowToken=null
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
,D/PMN     (  905): onScreenOn
,I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  905): acquireWL(44837a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(44837a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,D/NfcService( 1262): applyRouting - 0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/MtpService( 1967): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 1967): [MTP][onReceive]-
,D/NfcService( 1262): applyRouting -2
,W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/PMS     (  905): acquireWL(43a457b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/PMS     (  905): releaseWL(43a457b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4580 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4071
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): SET_SCREEN_ON:On
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
I/ActivityManager(  905): Killing 4071:com.google.android.talk/u0a111 (adj 15): empty #17
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/dalvikvm( 4517): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4517): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/ClockThread( 1118): stop update clock
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
E/dalvikvm( 4517): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4517): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
E/dalvikvm( 4517): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4517): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 96
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
V/SRS_Proc(  370): ParamSet string: screen_state=on
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
E/dalvikvm( 4517): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4517): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4517): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4517): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4517): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/dalvikvm( 4517): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4517): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4517): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4517): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4517): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4517): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4517): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  905): updateScreenOn: false
,I/dalvikvm-heap( 4517): Grow heap (frag case) to 9.966MB for 84664-byte allocation
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4580): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4580): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1160): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1160): EAPOL: disable timer tick
,W/GAV2    ( 4580): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4580): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4580): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4517): Grow heap (frag case) to 9.991MB for 39954-byte allocation
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/PMS     (  905): acquireWL(443c5868): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(443c5868): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43866918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1742): onScreenOn: false
D/PMS     (  905): releaseWL(43866918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): onScreenOn: 1452292048588
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1742): onScreenOn: 1452292048588
I/ActivityManager(  905): Recipient 4071
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42a70b70
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42a70b70, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@42daf648
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(43bc8210): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,I/dalvikvm-heap( 4517): Grow heap (frag case) to 10.018MB for 28144-byte allocation
,I/dalvikvm-heap( 4517): Grow heap (frag case) to 10.094MB for 79892-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4580/10151)
,V/WebViewChromiumFactoryProvider( 4580): Binding Chromium to main looper Looper (main, tid 1) {422630c8}
,I/LibraryLoader( 4580): Expected native library version number "",actual native library version number ""
,I/chromium( 4580): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4580): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(43eea518): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  905): acquireWL(441d6478): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4580): BLUETOOTH permission is missing!
D/PMS     (  905): releaseWL(43eea518): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4580): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4580): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4580): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4580): Local Branch: 
I/Adreno-EGL( 4580): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4580): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4580):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4580): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4580/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4580/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4111/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4111/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,I/iu.Environment( 2179): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/dalvikvm-heap( 4517): Grow heap (frag case) to 10.282MB for 75760-byte allocation
,I/iu.UploadsManager( 2179): num queued entries: 0
,I/iu.UploadsManager( 2179): num updated entries: 0
,I/iu.SyncManager( 2179): NEXT; no task
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44183320 u0 ReceiverList{44183200 4517 com.facebook.katana/10027/u0 remote:44182d40}}
,D/AutoSetting( 1331): receiver - intent: android.intent.action.USER_PRESENT
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44183320 u0 ReceiverList{44183200 4517 com.facebook.katana/10027/u0 remote:44182d40}}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{443498b8 u0 ReceiverList{43f27100 4517 com.facebook.katana/10027/u0 remote:443d6fb8}}
,D/AutoSetting( 1331): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/TetherSettings( 4133): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4133): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4133): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4133): Cust_ConnectToPC   : spcsc>false
D/        ( 4133): Cust_ConnectToPC   : IPT>true
,D/        ( 4133): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4133): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,E/SmartNS_Utility( 4133): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4133): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4133): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4133): onReceive:android.intent.action.USER_PRESENT
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
W/ContextImpl( 4133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
,I/SmartNS_PSService( 4133): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4133): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4133):  defaultType:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/Process (  905): killProcessQuiet, pid=4285
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4285:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20088 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): SET_SCREEN_ON:Off
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1160): get_ip_address source addr = 02000000
I/wpa_supplicant( 1160): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/PMS     (  905): acquireWL(43a1c0e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
I/ActivityManager(  905): Recipient 4285
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): releaseWL(43a1c0e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  905): updateScreenOn: false
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4625 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ContactMessageStore( 1248): start background delete task...
D/ContactMessageStore( 1248): size: 0 , 0
D/ContactMessageStore( 1248): Background delete complete
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): acquireWL(444a18e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4625): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(444a18e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/AutoSetting( 1331): service - mHandler: cancel location update
D/AutoSetting( 1331): service -           changes count: 0
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/SmartSyncUtils( 4625): isEpsOn(), nState = 0
D/DotMatrix( 1559): [EventService] getTotalRam: 1873 Mb
D/PMS     (  905): acquireWL(439f8190): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4625 1000 null
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/PMS     (  905): acquireWL(43d12160): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43d12160): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(442c0e00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(439f8190): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  905): releaseWL(442c0e00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4625): getMobilePolicyEnabled, result = true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1742): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1742): onScreenOff
,D/Process (  905): killProcessQuiet, pid=4316
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4316:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4316
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4625): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4625): isEpsOn(), nState = 0
D/SmartSyncUtils( 4625): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4625): isEpsOn(), nState = 0
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{443e38c0 u0 com.test.thalitest/.MainActivity t2}
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42daf648
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42daf648, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42daf648, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42daf648
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/WifiService(  905): New client listening to asynchronous messages
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42d1f588 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42d1f588 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(443d3720): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 168
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1160): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  905): WAN detection
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4133): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@42c0f5b8
,D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1160): Change stage from stage0 to stage3
D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(448215b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4544/10079)
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:2
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  905): acquireWL(445d59c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1452292002179 min interval config: 0 actual interval: 47204
D/PMS     (  905): acquireWL(4458c110): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(445d59c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2179): Checking schedule, now: 1452292049389 next: 1452292032139
,I/CheckinService( 2179): active receiver: enabled
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2179, uid=10029, userID:0
,I/CheckinService( 2179): Preparing to send checkin request
,I/EventLogService( 2179): Accumulating logs since 1452291997315
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(448215b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4686 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4686): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4686): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4686): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4686): install
,I/MultiDex( 4686): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4686): loading existing secondary dex files
,I/MultiDex( 4686): load found 3 secondary dex files
,I/MultiDex( 4686): install done
,W/dalvikvm( 4686): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4686): VFY: unable to resolve instance field 36
,W/dalvikvm( 4686): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4686): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4686): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4686): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4686): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1226): callingUid 10029, callindPid: 1226
,W/dalvikvm( 4686): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/LocationInitializer( 2179): Restart initialization of location
E/dalvikvm( 4686): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4686): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4686): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4686): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/AuthorizationBluetoothService( 1348): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1348): Proximity feature is not enabled.
,E/MDM     ( 1226): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  905): acquireWL(42ba3590): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1226): No location to return for getLastLocation()
,W/FusedLocationProvider( 1226): location=null
D/PMS     (  905): releaseWL(42ba3590): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4686): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2463871690
,I/WVCdm   (  370): CdmEngine::CloseSession
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/Settings( 4686): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4686): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4686): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4686): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4686): Local Branch: 
I/Adreno-EGL( 4686): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4686): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4686):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  905): releaseWL(4444c460): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42642580): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/PMS     (  905): releaseWL(42642580): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1571/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
D/CaptivePortalTracker(  905): NoActiveNetworkState
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 3884): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  370): CdmEngine::OpenSession
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3884/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4544/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/PMS     (  905): acquireWL(43e1c160): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3924/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1571/10029)
,D/AccTypeManager( 1367): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43e1c160): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1967/10021)
,W/AccTypeManager( 1367): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1367): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1367): Unsupported attribute readOnly
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1331): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2715460640
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1331/10055)
D/MobileConnectivityChangeReceiver( 4544): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/AutoSetting( 1331): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/MobileConnectivityChangeReceiver( 4544): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1331): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1331): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1331): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1331/10055)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4580/10151)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4111/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4111/10160)
,D/PMS     (  905): acquireWL(448ed160): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1452292002179 min interval config: 0 actual interval: 48308
,D/PMS     (  905): releaseWL(448ed160): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4111): Grow heap (frag case) to 13.518MB for 1821008-byte allocation
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/iu.Environment( 2179): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2179): num queued entries: 0
,I/iu.UploadsManager( 2179): num updated entries: 0
,I/iu.SyncManager( 2179): NEXT; no task
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/libc    ( 1348): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1348): [NET] getaddrinfo-,err=8
D/libc    ( 1348): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1348): [NET] getaddrinfo-, 1
,D/libc    ( 1348): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =c252 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  905): acquireWL(443d9a88): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 6
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1348): [NET] getaddrinfo_proxy-, success,
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4686/10029)
,D/libc    ( 1348): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1348): [NET] getaddrinfo-,err=8
,I/Adreno-EGL( 4686): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4686): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4686): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4686): Local Branch: 
I/Adreno-EGL( 4686): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4686): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4686):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4686): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4686): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4686): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4686): Local Branch: 
I/Adreno-EGL( 4686): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4686): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4686):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1348): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1348): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/PMS     (  905): acquireWL(43c059a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/PMS     (  905): releaseWL(443d9a88): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1348/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/PMS     (  905): releaseWL(43c059a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(443497f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1348/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1348/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): releaseWL(443497f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2179): [NET] getaddrinfo-,err=8
D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2179): [NET] getaddrinfo-, 1
,D/libc    ( 2179): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5c76 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 112
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2179): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2179): Sending checkin request (12199 bytes)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,W/fb4a(:<default>):UserScope( 4517): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4517): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=35 [20][7][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=16 [6][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,E/fb4a(:<default>):LocalFbBroadcastManager( 4517): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,D/libc    ( 4517): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4517): [NET] getaddrinfo-,err=8
D/libc    ( 4517): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4517): [NET] getaddrinfo-, 1,
D/libc    ( 4517): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  363): [NET] +++++ res_nsend xid =dc82 +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 36,
D/libc    (  363): [NET]res_nsend:resplen=74
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2,
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4517): [NET] getaddrinfo_proxy-, success
I/global  ( 4517): call createSocket() return a new socket.,
D/libc    ( 4517): [NET] getaddrinfo+,hn 10(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4517): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4517): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4517): [NET] getaddrinfo-,err=8
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  905): releaseWL(441d6478): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/dalvikvm-heap( 4517): Grow heap (frag case) to 11.005MB for 32784-byte allocation
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=18 [16][3][0]
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
,I/CheckinTask( 2179): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/PMS     (  905): acquireWL(43dc9068): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4517 10027 null
,I/CheckinService( 2179): Checking schedule, now: 1452292051827 next: 1452814988817
,I/CheckinService( 2179): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
I/CheckinService( 2179): Checking schedule, now: 1452292051849 next: 1452814988817
,I/CheckinService( 2179): active receiver: disabled
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,D/CheckinService( 2179): Recording last checkin time for package unspecified as 1452292051858
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/PMS     (  905): releaseWL(4458c110): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/GCM     ( 1348): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4517/10027)
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =41e0 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4,
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success,
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175,
,I/global  ( 4517): I/O error closing connection
I/global  ( 4517): java.net.SocketException: Socket is closed
I/global  ( 4517): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4517): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4517): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4517): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4517): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4517): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4517): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4517): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4517): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4517): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4517): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4517): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4517): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4517): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4517): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4517): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4517): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4517): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4517): Removing a connection that never existed!
D/PMS     (  905): releaseWL(43dc9068): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/GAV2    ( 4580): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager(  905): Sleep timeout!  Sleeping now.
,D/PMS     (  905): releaseWL(43bc8210): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/jxcore-log( 4464): Test app app.js loaded
I/jxcore-log( 4464): 
,I/Choreographer( 4464): Skipped 522 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4464): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4464): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{4226bf68 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4464): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Process (  905): killProcessQuiet, pid=4341
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4341:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4341
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1518): service - handleMessage() stop self
,D/AutoSetting( 1518): service - onDestroy() END
,D/AutoSetting( 1518): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4303
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4303:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4303
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1367): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4736 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1276): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/Launcher( 1276): Deferring update until onResume
,D/Launcher( 1276): waitUntilResume // bindAppsUpdated
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1367): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1367): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
E/ExternalAccountType( 1367): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4736): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4736): MmsConfig.loadMmsSettings
,W/dalvikvm( 4736): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4736): VFY: unable to resolve instance field 36
,W/dalvikvm( 4736): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4736): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4759 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4736, uid=10111, userID:0
,D/MessageFrequencyProvider( 4759): onCreate
,W/Settings( 4736): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GetPrviateResource( 4759): GetPrviateResource
V/GetPrviateResource( 4759): GetPrviateResource
,D/MmsCustomizationProvider( 4759): query uri: content://htc-mms-customization/mms-ua/ua_string
,W/PackageManager(  905): Unable to load service info ResolveInfo{438166e8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4736, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4736, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4736, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4736, uid=10111, userID:0
,D/MmsCustomizationProvider( 4759): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4736, uid=10111, userID:0
,I/Babel   ( 4736): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4736): MmsConfig.loadFromDatabase
D/PMS     (  905): acquireWL(44461380): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4736 10111 null
,E/Babel   ( 4736): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4736): MmsConfig.loadFromResources
,E/Babel   ( 4736): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4736): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/[PluginManager]RegisterService( 1331): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1331): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2855): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ProviderInstaller( 4736): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(448071f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4111 10160 null
,D/MessageCustFlag( 4759): sense_version=6.0
,D/BTAccessoryUtil( 4759): createReceiver
D/PMS     (  905): releaseWL(44461380): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/BTAccessoryUtil( 4759): registerReceiver return intent = null
D/MessageCustFlag( 4759): sku_id=99
,W/SystemReader( 4759): Cannot find message_ambs_application_id, use default value instead
,I/dalvikvm-heap( 4111): Grow heap (frag case) to 15.218MB for 1821008-byte allocation
D/PMS     (  905): acquireWL(43f7ae68): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(448071f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): releaseWL(43f7ae68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/Messaging( 4759): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4759): networkCode: 
D/MessageCustFlag( 4759): sku_id=99
D/MmsConfig( 4759): SIE smsPri: null
D/MmsConfig( 4759): networkCode: 
,D/HtcTelephonyCapability( 4759): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4759): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4759): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4759): Cannot find qct_8960_interface, use default value instead
,I/dalvikvm-heap( 4111): Grow heap (frag case) to 16.950MB for 1821008-byte allocation
D/PMS     (  905): acquireWL(4287b5e0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=4360
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4360:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4360
,D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2179): Null package name or gms related package.  Ignoreing.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 2179): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(43a3db78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): releaseWL(43a3db78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43de90e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43de90e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43bfa4e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43bfa4e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2855): UpdateCorporaTask done [took 531 ms] updated apps [took 531 ms] 
,D/PMS     (  905): acquireWL(449d5af8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(449d5af8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@422f3cd0 +
,I/Prism.WidgetManager( 1276): onLoadItems() +
,I/Icing   ( 2179): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2179): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(4287b5e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1276): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1276): onLoadItems() -
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@422f3cd0 -
,D/PhoneApp( 1248): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1248): -- N1 =0
,D/PhoneApp( 1248): -- N2 =0
,D/PhoneApp( 1248): -- N3 =0
,D/Messaging( 4759): mNeedToUpdateDate2 start
,D/MmsConfig( 4759): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4759): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4759): 
D/MmsAsyncWorkHandler( 4759): HM tk = 20001
,D/ReportIndicatorCache( 4759): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4759): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@42270408
,I/Messaging( 4759): mccmnc> 
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/DraftCache( 4759): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4759): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4759): networkCode: 
,D/Messaging( 4759): ViewCache CreatePreloadOnlyConversationList
,D/PhoneStorageUtil( 4759): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4759): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4759): createReceiver
,D/MessageCustFlag( 4759): sense_version=6.0
,D/Jerry   ( 4759): start to preload cursor >>>>>>>
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4759): mNeedToUpdateDate2: false
D/TelephUtils( 1248): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/MmsProvider( 1248): Update uri=content://mms, match=0
,V/MmsProvider( 1248): selection=st=129 AND m_type!=134
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/Messaging( 4759): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4759): TransactionService is going to be woken up.
,V/TransactionService( 4759): 1-Creating TransactionService
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1248): sku_id=99
D/Messaging( 4759): ViewCache CreatePreload
,D/Messaging( 4759): ViewCache CreatePreloadOnlyMultipleOpsList
D/Cust_MMSMS( 4759): _has_set_default_values_2=true
V/TransactionService( 4759): onStartCommand: 1
,D/MmsSystemEventReceiver( 4759): unRegisterForConnectionStateChanges
V/TransactionService( 4759): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4759): Loading previous transactions.
,D/DraftCache( 4759): [DraftCache/472] rebuildCache
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MsgPreferenceUtils( 4759): def_index: 0
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1248): device_type: 1
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Jerry   ( 1248): URI_DRAFT
,D/MsgPreferenceUtils( 4759): globalIndex = 1
D/TransactionService( 4759): Force set service start id to 1
V/TransactionService( 4759): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4759): unRegisterForConnectionStateChanges
,V/TransactionService( 4759): Destroying TransactionService
,D/TransactionService( 4759): stopSelfResult: true, mLastHandledServiceId: 1
D/MsgPreferenceUtils( 4759): phone state: true
D/MsgPreferenceUtils( 4759): sd state: false
,D/MsgPreferenceUtils( 4759): vIndex = 0
,V/TransactionService( 4759): 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/DraftCache( 4759): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4759): [DraftCache/472] rebuildCache time: 3
,D/MmsAsyncWorkHandler( 4759): 
D/MmsAsyncWorkHandler( 4759): HM tk = 20002
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4759): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1248): sku_id=99
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1248): sku_id=99
,D/Process (  905): killProcessQuiet, pid=3924
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3924:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3924
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV4    ( 4736): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(44834738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/BatteryService(  905): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(44834738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(445d5ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(445d5ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(44495d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{42c78cc0: PendingIntentRecord{4234a8e0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122359, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{442fc9d8: PendingIntentRecord{42e785f0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=133390, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{443ca870: PendingIntentRecord{42ad7ae8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452292076256, Int=1800000
,D/PMS     (  905): acquireWL(44463290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [26][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(444565d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(444565d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44463290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44444298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): releaseWL(44444298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(444441a8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44444158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/PMS     (  905): releaseWL(44495d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(44444018): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(444441a8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,I/EventLogService( 2179): Aggregate from 1452292049428 (log), 1452290276216 (data)
,D/PMS     (  905): acquireWL(427f2600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): releaseWL(44444018): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42b1ee38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1226): Vacuum at: now=1452292079338 tag=VacuumService
,D/PMS     (  905): releaseWL(44444158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(427f2600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42672dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): releaseWL(42672dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(427aa1a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42b1ee38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): releaseWL(427aa1a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42d754b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862,
,D/PMS     (  905): releaseWL(42d754b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42af35f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): releaseWL(42af35f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(437da290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): acquireWL(42cfeb20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42cfeb20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42cd80a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(437da290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42df2d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271,
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): releaseWL(42df2d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43a5c0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42433050: PendingIntentRecord{42acf988 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=134322, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
,D/PMS     (  905): releaseWL(43a5c0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1226): Scheduling Phenotype for one-off execution 11014 seconds from now (1452292080153)
,D/GetConfigurationSnapshotOperation( 1226): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1226): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1226): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1331): service - has update message, not stop
,D/AutoSetting( 1331): service - mHandler: update timezone
,D/AutoSetting( 1518): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1518): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1518): service - onCreate()
D/AutoSetting( 1518): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1518): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1518): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1518): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1518): service - mHandler: update timezone
,D/DotMatrix( 1559): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1518): service - processTimeZoneID() system nitz: 
D/AutoSetting( 1518): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1518): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1518): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{423b30d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 1 9 2 11
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
D/libc    ( 1226): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3521 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 12
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [11][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(42cd80a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44375e90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): releaseWL(44375e90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42a6d940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1348/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): releaseWL(42a6d940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(448a2ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42b683d8: PendingIntentRecord{42b68358 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141614, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/PMS     (  905): acquireWL(42d7aca0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): releaseWL(448a2ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7b75 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4,
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  905): releaseWL(42d7aca0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43e84820 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1331): service - handleMessage() stop self
,D/AutoSetting( 1331): service - onDestroy() END
,D/AutoSetting( 1331): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4392
,I/ActivityManager(  905): Killing 4392:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4392
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1518): service - handleMessage() stop self
,D/AutoSetting( 1518): service - onDestroy() END
,D/AutoSetting( 1518): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4406
,I/ActivityManager(  905): Killing 4406:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4406
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(43c45268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c45268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43c854c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c854c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(44972f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42433050: PendingIntentRecord{42acf988 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=194322, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44972f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43fbae18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{42d2e4d8: PendingIntentRecord{4410cad8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=223125, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4842 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{42d34d50: PendingIntentRecord{42ceb0f8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452292157096, Int=10800000
,D/PMS     (  905): releaseWL(43fbae18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  905): acquireWL(42dc59c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{42cce7a8: PendingIntentRecord{4410cad8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=223211, Int=0
,D/PMS     (  905): releaseWL(42dc59c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4842/10049)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/Process (  905): killProcessQuiet, pid=4036
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4036:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4036
,D/PMS     (  905): acquireWL(43ee3028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{43ca34c8: PendingIntentRecord{442f2598 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=223302, Int=120000
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024271
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024276
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024302
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024314
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028724
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029862
,D/PMS     (  905): releaseWL(43ee3028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(44822468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44822468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44397530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44397530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(448bb4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42433050: PendingIntentRecord{42acf988 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=254322, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(448bb4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4464): --= Surplus to requirements =--
I/jxcore-log( 4464): 
I/jxcore-log( 4464): ****TEST TOOK:  ms ****
I/jxcore-log( 4464): 
,I/jxcore-log( 4464): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4464): 
,E/cutils-trace( 4864): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4864): ====startRecUseTime====
D/htc.customization.log.level( 4864):  is 
,W/CustomizationLogLevel( 4864): Level value is invalid, use default level 2
,D/CustomizationManager( 4864):  Read ACC file spent 0.056 (s)
D/CIDMapFileReader( 4864): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4864): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4864): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4864): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4864): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4864): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4864): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4864): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4864): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4864): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4864): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4864): Parsing tag category name = system
I/CustomizationCIDLoader( 4864): Parsing tag category name = application
,I/CustomizationCIDLoader( 4864): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4864): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4864): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4864): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4864): Parsing tag category name = Settings
D/CustomizationManager( 4864):  Read CID file spent 0.094 (s)
,D/CustomizationManager( 4864):  All configurations done spent 0.094 (s)
W/HtcNativeFlag( 4864): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4864): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4864): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4864): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4864, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4464
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905): Killing 4464:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  905):   Force finishing activity ActivityRecord{443e38c0 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  905): Copying FileAsset 0x62fa2978 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1212): !!! FAILED BINDER TRANSACTION !!!
W/PackageSettings(  905): Skipping PackageSetting{4290e480 com.example.hello/10397} due to missing metadata
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4464 uid 10389
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/PMS     (  905): acquireWL(43facf90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,W/GeofencerStateMachine( 1226): Ignoring removeGeofence because network location is disabled.
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1367): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(43facf90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,D/VoicemailCleanupService( 1290): Cleaning up data for package: com.test.thalitest
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  905): channel '42cf8898 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '42cf8898 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '42cf8898 com.test.thalitest.MainActivity (s)'
I/WindowState(  905): WIN DEATH: Window{42cf8898 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  905): Client connection lost with reason: 4
,I/WindowManager(  905): WINDOW DIED Window{42cf8898 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/AccTypeManager( 1367): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1367): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1276): Deferring update until onResume
,D/Launcher( 1276): waitUntilResume // bindAppsRemoved
,D/Prism.PackageStateRece_( 1276): action: android.intent.action.PACKAGE_REMOVED
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/[PluginManager]RegisterService( 1331): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1331): handle notify Blinkfeed plugin client changed
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
,I/IcingCorporaProvider( 2855): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,E/ExternalAccountType( 1367): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  905):   Scheme: "smsto"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  905):   Scheme: "mms"
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4879 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  905): acquireWL(4488f378): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4488f378): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(448212b0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2855): UpdateCorporaTask done [took 315 ms] updated apps [took 315 ms] 
,W/PackageManager(  905): Unable to load service info ResolveInfo{4279de00 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4899 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=4442
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4442:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4879/10100)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4879/10100)
E/SQLiteLog( 4879): (3850) statement aborts at 59: [DELETE FROM CachedSearch111 WHERE timestamp<?] disk I/O error
,E/SQLiteDBG( 4879): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.apps.docs/databases/DocList.db, handle = 0x5ca229a0
E/AbstractDatabaseInstance( 4879): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 4879): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 4879): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 4879): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AbstractDatabaseInstance( 4879): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AbstractDatabaseInstance( 4879): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 4879): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AbstractDatabaseInstance( 4879): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 4879): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 4879): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 4879): 	at fv.run(DocsApplication.java:288)
,W/dalvikvm( 4879): threadid=11: thread exiting with uncaught exception (group=0x41e30e30)
,W/GAV2    ( 4879): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  905): Recipient 4442
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/AndroidRuntime( 4879): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4879): Process: com.google.android.apps.docs, PID: 4879
E/AndroidRuntime( 4879): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4879): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4879): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4879): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4879): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4879): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4879): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime( 4879): 	at aid.a(DatabaseModelLoader.java:340)
E/AndroidRuntime( 4879): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime( 4879): 	at fv.run(DocsApplication.java:288)
,E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/Process ( 4879): killProcess, pid=4879
,D/Process ( 4879): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/RemoteDisplayProvider(  905): start
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
,W/ContextImpl( 4899): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Recipient 4879
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4879) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
,I/ActivityManager(  905): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
,E/SQLiteDatabase( 4899): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4899): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4899): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4899): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4899): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4899): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4899): threadid=10: thread exiting with uncaught exception (group=0x41e30e30)
W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/ActivityManager(  905): App crashed! Process: com.android.keychain
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/AndroidRuntime( 4899): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4899): Process: com.android.keychain, PID: 4899
E/AndroidRuntime( 4899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4899): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4899): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4899): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4899): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4899): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4899): killProcess, pid=4899
D/Process ( 4899): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452292247364.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  905): Recipient 4899
I/ActivityManager(  905): Process com.android.keychain (pid 4899) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10920ms
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4922 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,D/AppTag  ( 4922): getInstance(Context context)
,D/AppTag  ( 4922): getInstance(Context context)
,D/AppTag  ( 4922): onCreate()
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(42beb7e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4111 10160 null
,D/PMS     (  905): releaseWL(42beb7e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,W/dalvikvm( 4149): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2179): Clearing selected account for com.test.thalitest
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/LocationSettingsChecker( 2179): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 2179): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2179): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x656d0a00
,E/DriveAsyncService( 2179): disk I/O error (code 3850)
E/DriveAsyncService( 2179): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2179): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2179): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2179): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2179): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2179): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 2179): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2179): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2179): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2179): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2179): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2179): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2179): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2179): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2179): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2179): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2179): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase( 2179): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2179): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2179): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2179): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2179): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2179): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2179): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2179): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2179): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2179): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2179): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2179): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2179): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2179): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2179): 	at com.google.a,ndroid.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2179): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2179): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2179): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2179): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2179): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2179): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2179): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2179): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2179): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2179): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2179): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2179): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2179): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2179): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2179): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2179): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2179): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 2179): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 2179): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 2179): threadid=50: thread exiting with uncaught exception (group=0x41e30e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
D/Process ( 2179): killProcess, pid=2179
E/AndroidRuntime( 2179): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 2179): Process: com.google.android.gms, PID: 2179
E/AndroidRuntime( 2179): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2179): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 2179): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 2179): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2179): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2179): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2179): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2179): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/BaseAppContext( 2179): Using Auth Proxy for data requests.
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
,I/ActivityManager(  905): Recipient 2179
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.google.android.gms (pid 2179) has died.
D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): handleWLDeath(448212b0): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10505ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20505ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20504ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20504ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 30503ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 40503ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 40502ms
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@422f3cd0 +
,I/Prism.WidgetManager( 1276): onLoadItems() +

```
