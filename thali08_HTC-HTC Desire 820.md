#### Test 549702610b97681_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
E/cutils-trace( 4355): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4355): ====startRecUseTime====
D/htc.customization.log.level( 4355):  is 
W/CustomizationLogLevel( 4355): Level value is invalid, use default level 2
D/CustomizationManager( 4355):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 4355): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4355): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4355): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4355): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4355): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4355): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4355): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4355): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4355): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4355): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4355): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4355): Parsing tag category name = system
I/CustomizationCIDLoader( 4355): Parsing tag category name = application
I/CustomizationCIDLoader( 4355): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4355): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4355): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4355): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4355): Parsing tag category name = Settings
D/CustomizationManager( 4355):  Read CID file spent 0.091 (s)
D/CustomizationManager( 4355):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 4355): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4355): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4355): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4355): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4355
D/PMS     (  905): acquireHCC(424be5a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(4246f2d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1112610280
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d36c38
I/SocialFeedProvider( 1275): +onPause
I/SocialFeedProvider( 1275): -onPause
D/PMS     (  905): acquireWL(4211a930): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4366 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1275): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4366): Binding Chromium to main looper Looper (main, tid 1) {41c19a40}
I/LibraryLoader( 4366): Expected native library version number "",actual native library version number ""
I/chromium( 4366): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4366): Initializing chromium process, renderers=0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4262e868:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4366): 1103298680: getState(). Returning 12
D/PMS     (  905): acquireWL(425228e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): acquireWL(4273dbf8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): releaseWL(425228e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4366): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4366): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4366): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4366): Local Branch: 
I/Adreno-EGL( 4366): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4366): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4366):                  aa63bbd948f41d15fc72f585e
W/chromium( 4366): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4366): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4366): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4366): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4366): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4366): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4366): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4366): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4366): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4366): CordovaWebView is running on device made by: HTC
,W/AwContents( 4366): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1275
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +256ms
W/ResourceType( 4366): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4366): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41c61728, mServedView=org.apache.cordova.engine.SystemWebView{41c27390 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  905): Enable input method client, pid=4366
W/AwContents( 4366): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  905): releaseWL(4211a930): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4366): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4366): JniHelper::setJavaVM(0x417da010), pthread_self() = 1663065304
,D/JX-Cordova( 4366): jxcore cordova android initializing
,I/dalvikvm-heap( 4366): Grow heap (frag case) to 11.532MB for 63974-byte allocation
,D/WIFI_ICON( 1117): WifiActivity: 0
,I/dalvikvm-heap( 4366): Grow heap (frag case) to 11.590MB for 95956-byte allocation
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4366): Grow heap (frag case) to 11.660MB for 143930-byte allocation
,I/dalvikvm-heap( 4366): Grow heap (frag case) to 11.775MB for 215890-byte allocation
,I/dalvikvm-heap( 4366): Grow heap (frag case) to 11.950MB for 323830-byte allocation
,I/dalvikvm-heap( 4366): Grow heap (frag case) to 12.625MB for 728606-byte allocation
,I/dalvikvm-heap( 4366): Grow heap (frag case) to 13.222MB for 1092904-byte allocation
,I/dalvikvm-heap( 4366): Grow heap (frag case) to 14.090MB for 1639352-byte allocation
,I/dalvikvm-heap( 4366): Grow heap (frag case) to 15.446MB for 2459024-byte allocation
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{434cd138 u0 com.htc.htclocationservice/.AutoSettingService}
,I/dalvikvm-heap( 4366): Grow heap (frag case) to 17.487MB for 3688532-byte allocation
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/jxcore-log( 4366): Initializing JXcore engine
W/jxcore-log( 4366): JXcore engine is ready
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(424be5a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(4246f2d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4366): Starting JXcore engine
,W/jxcore-log( 4366): Platform android
W/jxcore-log( 4366): 
,W/jxcore-log( 4366): Process ARCH arm
W/jxcore-log( 4366): 
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4408 uid=10077 gids={50077}
D/PMS     (  905): acquireWL(424e6fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
V/AlarmManager(  905): sending alarm PendingIntent{424c03c0: PendingIntentRecord{4236cde0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452294314969, Int=60000
,D/PMS     (  905): releaseWL(424e6fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4408): SMSBackupAgentService started
,D/SMSBackup( 4408): Checking restore status
D/SMSBackup( 4408): Restore complete
,D/SMSBackup( 4408): cancelCheckAlarm
,D/SMSBackup( 4408): SMSBackupAgentService completed: completed in 0.0 seconds
,I/ActivityManager(  905): Killing 3117:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=3117
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3117
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/jxcore-log( 4366): JXcore Cordova bridge is ready!
I/jxcore-log( 4366): 
,W/jxcore-log( 4366): JXcore engine is started
,I/chromium( 4366): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4366): Toggling radios to true
I/jxcore-log( 4366): 
,D/BluetoothAdapter( 4366): enable(): BT is already enabled..!
,D/WifiManager( 4366): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1405
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
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
,D/WifiManager( 4366): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4366): reconnect: Base Package Name=com.test.thalitest, uid=10348
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4366, uid=10348
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): TDLS: Tear down peers
I/wpa_supplicant( 1157): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4366): Radios toggled
I/jxcore-log( 4366): 
I/jxcore-log( 4366): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4366): 
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1157): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1157): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1157): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb82b4bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1157):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1157): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
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
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1157): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generat,ed=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1157): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  905):    returned true
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(4374a258): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): Fast associate: Old scan results
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): State: DISCONNECTED -> SCANNING
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19335 mDataStallAlarmIntent=PendingIntent{425cf758: PendingIntentRecord{42480cf0 android broadcastIntent}}
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): Enter handleNetworkDisconnect
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4139): >>>>>WISPrService start isConnected = false<<<<<
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4139): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiService(  905): New client listening to asynchronous messages
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
,D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] entry_id:5   entry:0xb75ce818  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb75ce2d8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb75ce108  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb75ce760  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb75ce1d0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb75ce410  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb75ce8e0  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/PMS     (  905): acquireWL(42eeeb38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1384 10028 null
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
,D/WISPrService( 4139): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4139): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  905): acquireWL(43611590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1384 10028 null
D/PMS     (  905): releaseWL(43611590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:2
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/PMS     (  905): acquireWL(42e521a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1384/10028)
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  905): releaseWL(42eeeb38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/PMS     (  905): releaseWL(42e521a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,D/PMS     (  905): releaseWL(4273dbf8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  905): acquireWL(42efd0a8): PARTIAL_WAKE_LOCK  Icing 0x1 2256 10028 null
,D/PMS     (  905): releaseWL(42efd0a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(441e4320): PARTIAL_WAKE_LOCK  Icing 0x1 2256 10028 null
,D/PMS     (  905): releaseWL(441e4320): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(43568e90): PARTIAL_WAKE_LOCK  Icing 0x1 2256 10028 null
,D/PMS     (  905): releaseWL(43568e90): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(421f8e20): PARTIAL_WAKE_LOCK  Icing 0x1 2256 10028 null
,D/PMS     (  905): releaseWL(421f8e20): PARTIAL_WAKE_LOCK  Icing 0x1 null
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
,I/NetworkMonitor( 3857): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3857/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4255/10100)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10075)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): acquireWL(43e2ec70): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1488/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4255/10100)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2448/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4434 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  905): releaseWL(43e2ec70): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4434): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4434): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4434): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4434): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4434): Preparing secondary program dexes.
V/DexLibLoader( 4434): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4434): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4434): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4434): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4434): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4434): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4434): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4434): Dex already copied
D/OdexVerifier( 4434): Odex verification is skipped.
,V/DexLibLoader( 4434): Creating class loader
,V/DexLibLoader( 4434): Finished creating class loader
V/DexLibLoader( 4434): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4434): Dex already copied,
D/OdexVerifier( 4434): Odex verification is skipped.
,V/DexLibLoader( 4434): Creating class loader
V/DexLibLoader( 4434): Finished creating class loader
V/DexLibLoader( 4434): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4434): Dex already copied
D/OdexVerifier( 4434): Odex verification is skipped.
,V/DexLibLoader( 4434): Creating class loader
,V/DexLibLoader( 4434): Finished creating class loader
V/DexLibLoader( 4434): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4434): Dex already copied
D/OdexVerifier( 4434): Odex verification is skipped.
,V/DexLibLoader( 4434): Creating class loader
V/DexLibLoader( 4434): Finished creating class loader
,V/DexLibLoader( 4434): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4434): DexLibLoader.ensureDexLoaded took 17 ms
,W/dalvikvm( 4434): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4434): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4434): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4434): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4434): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4434): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4434): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1157): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1157): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1157): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1157): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
W/dalvikvm( 4434): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
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
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
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
D/wpa_supplicant( 1157): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb82b64e8  current_ssid=0x0
D/wpa_supplicant( 1157): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1157): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1157): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1157): check if in concurrent case
I/wpa_supplicant( 1157): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent ,SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1157): RSN: PMKSA cache search - network_ctx=0xb82b64e8 try_opportunistic=0
D/wpa_supplicant( 1157): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1157): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1157): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1157): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1157): nl80211: Unsubscribe mgmt frames handle 0xb82b5718 (mode change)
D/wpa_supplicant( 1157): nl80211: Subscribe to mgmt frames with non-AP handle 0xb82b5718
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb82b5718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb82b5718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb82b5718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb82b5718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb82b5718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb82b5718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb82b5718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb82b5718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb82b5718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb82b5718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1157):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157):   * freq=2412
D/wpa_supplicant( 1157):   * Auth Type 0
D/wpa_supplicant( 1157):   * WPA Versions 0x2
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1157): nl80211: Connect request send successfully
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
D/WirelessDisplayService(  905): getDiscoveryDongleList
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1157): reply (489) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000106650998
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000106651015
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000106651018
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=3
I/wpa_supplicant( 1157): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000106651010
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1157): ssid=01ABC
I/wpa_supplicant( 1157): ####
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 106650998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 106651015, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 106651018, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 106651010, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/dalvikvm( 4434): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
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
D/wpa_supplicant( 1157): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1157): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1157): TDLS: Remove peers on association
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
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
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1157): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1157): Get randomness: len=32 entropy=5
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:,d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/wpa_supplicant( 1157): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb82b59f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1157):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1157): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f94b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1157):    broadcast key
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1157): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1157): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1157): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1157): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=6
,I/wpa_supplicant( 1157): set send_ind_to_ndc = 0
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state SUCCESS,
,D/wpa_supplicant( 1157): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1157): EAPOL authentication completed successfully
I/wpa_supplicant( 1157): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,E/FbInjectorInitializer( 4434): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4139): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WISPrService( 4139): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=100 [2][2][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 1
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(4352ea80): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424cd6b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424cd6b0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4434): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4434): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4434): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=3837
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3837:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  905): acquireWL(436a9880): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2256 10028 null
,I/ActivityManager(  905): Recipient 3837
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(43867750): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2256 10028 null
,D/PMS     (  905): releaseWL(436a9880): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,D/GCM     ( 1384): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,D/PMS     (  905): releaseWL(43867750): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1441): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4463 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1441/10053)
,D/AutoSetting( 1441): Util - no network available!
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1441/10053)
D/AutoSetting( 1441): service - onCreate()
D/AutoSetting( 1441): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1441): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  905): request 42659fb8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1441): service - mHandler: cancel location update
D/AutoSetting( 1441): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4434): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4434): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4434): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4463): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4463): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4463): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4463): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4481 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4463/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4463/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4463/10078)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4434): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4514 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4196
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4196:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 9.960MB for 84664-byte allocation
E/dalvikvm( 4434): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4434): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4434): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4434): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4514): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4514): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4514): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4514): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4514): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
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
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 9.975MB for 28144-byte allocation
E/dalvikvm( 4434): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4434): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4434): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4434): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4434): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/dalvikvm( 4434): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4434): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  905): releaseWL(4352ea80): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
W/dalvikvm( 4434): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4434): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4434): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4434): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4434): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4434): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4434): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1157): Change stage from stage0 to stage3
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1157): wlan0: Background scan every 600 seconds
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19337 delay=15s
,D/WifiWatchdogStateMachine(  905): WAN detection
E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
I/ActivityManager(  905): Recipient 4196
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@4254cd08
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/WISPrService( 4139): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 10.022MB for 39954-byte allocation
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0,
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(43c31bf0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4463/10078)
,D/PMS     (  905): acquireWL(43ce88c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2256 10028 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  905): acquireWL(440ffbb8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2256 10028 null
,D/PMS     (  905): releaseWL(43ce88c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/CheckinService( 2256): Preparing to send checkin request
,I/EventLogService( 2256): Accumulating logs since 1452294269451
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 10.099MB for 79892-byte allocation
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4514/10151)
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43c31bf0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/WebViewChromiumFactoryProvider( 4514): Binding Chromium to main looper Looper (main, tid 1) {41c1f328}
,I/GoogleHttpClient( 2256): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 2256): Using GMS GoogleHttpClient
,I/LibraryLoader( 4514): Expected native library version number "",actual native library version number ""
,I/chromium( 4514): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4514): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(443ccb30): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  905): acquireWL(441ee290): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4514): BLUETOOTH permission is missing!
D/PMS     (  905): releaseWL(443ccb30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2256/10028)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4514): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4514): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4514): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4514): Local Branch: 
I/Adreno-EGL( 4514): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4514): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4514):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2256/10028)
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 10.260MB for 75760-byte allocation
,W/GLSUser ( 1384): GoogleAccountDataService.getToken()
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
D/wpa_supplicant( 1157): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1157): EAPOL: disable timer tick
,I/NSApplication( 4514): Starting up...
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{432020b8 u0 ReceiverList{4269a7b8 4434 com.facebook.katana/10026/u0 remote:424c0960}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{432020b8 u0 ReceiverList{4269a7b8 4434 com.facebook.katana/10026/u0 remote:424c0960}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e72ac8 u0 ReceiverList{42613608 4434 com.facebook.katana/10026/u0 remote:424440f0}}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4514/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4514/10151)
,W/GLSActivity( 1384): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1384): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1384): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/Process (  905): killProcessQuiet, pid=4225
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/CheckinRequestBuilder( 2256): awaiting user notification for token
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
,I/ActivityManager(  905): Killing 4225:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/DotMatrix( 1571): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
I/ActivityManager(  905): Recipient 4225
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c75c48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 4 7 2 12
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
D/PMS     (  905): acquireWL(4358ea18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1488 10028 null
,D/GCM     ( 1384): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  905): releaseWL(4358ea18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4573 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/GCoreFlp( 1488): Unknown pending intent to remove.
D/PMS     (  905): acquireWL(432e88d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1488 10028 null
D/PMS     (  905): releaseWL(432e88d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/MultiDex( 4573): install
,I/MultiDex( 4573): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4573): loading existing secondary dex files
,I/MultiDex( 4573): load found 1 secondary dex files
,I/MultiDex( 4573): install done
,I/ProviderInstaller( 4573): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1384): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4434): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4434): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/SensorManager(  905): mEventCount = 1350
D/WIFI_ICON( 1117): WifiActivity: 3
D/PMS     (  905): releaseWL(4374a258): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1884): Checking Certificates
I/acms    ( 1884): Checking Developer Certificates
I/acms    ( 1884): Checking Application Certificates
I/acms    ( 1884): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
,I/acms    ( 1884): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
D/PMS     (  905): acquireWL(4264edd0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4463/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4255/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
I/acms    ( 1884): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1884): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1884): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1884): Updating next query delay: 75600000
I/mlserverapp( 1884): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1884): cancelACMSProgrammedChecks
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,W/Settings( 4573): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 3857): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1488/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3879/10051)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3857/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4255/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4573/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
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
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2448/10021)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=100 [1][1][0]
,D/PMS     (  905): acquireWL(424b0250): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2256 10028 null
,D/PMS     (  905): releaseWL(424b0250): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1384): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/libc    ( 1384): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1384): [NET] getaddrinfo-,err=8
D/libc    ( 1384): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1384): [NET] getaddrinfo-, 1
,D/libc    ( 1384): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2f03 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/PMS     (  905): acquireWL(435a3ee0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1384 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(425fb008): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/AutoSetting( 1441): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4463): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/PMS     (  905): releaseWL(425fb008): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): releaseWL(4264edd0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MobileConnectivityChangeReceiver( 4463): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1441/10053)
,D/AutoSetting( 1441): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1441): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1441): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1441): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1441): service - handleMessage() setting current location null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4514/10151)
,D/AutoSetting( 1441): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1441): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1441/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 235
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1384): [NET] getaddrinfo_proxy-, success
,I/Adreno-EGL( 4573): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4573): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4573): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4573): Local Branch: 
I/Adreno-EGL( 4573): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4573): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4573):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
,I/Adreno-EGL( 4573): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4573): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4573): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4573): Local Branch: 
I/Adreno-EGL( 4573): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4573): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4573):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1384): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1384): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/PMS     (  905): acquireWL(4346e0d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1384 10028 null
D/PMS     (  905): releaseWL(4346e0d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4573): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4573): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4573): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4573): Local Branch: 
I/Adreno-EGL( 4573): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4573): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4573):                  aa63bbd948f41d15fc72f585e
,D/GCM     ( 1384): Connected
D/PMS     (  905): acquireWL(44181838): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1384 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/PMS     (  905): releaseWL(435a3ee0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1384/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/PMS     (  905): releaseWL(44181838): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(436af110): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1384 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1384/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1384): Message class mpf
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1384/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/PMS     (  905): acquireWL(4268fa58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1384 10028 null
D/PMS     (  905): releaseWL(436af110): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): releaseWL(4268fa58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/CheckinTask( 2256): Sending checkin request (8839 bytes)
D/libc    ( 2256): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2256): [NET] getaddrinfo-,err=8
D/libc    ( 2256): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2256): [NET] getaddrinfo-, 1
,D/libc    ( 2256): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b13b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 200
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2256): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2256): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2256): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=3 [26][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42659270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1384 10028 null
,D/PMS     (  905): releaseWL(42659270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2256/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2256/10028)
D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,W/GLSUser ( 1384): GoogleAccountDataService.getToken()
,W/GLSActivity( 1384): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1384): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1384): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1571): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 2256): awaiting user notification for token
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41cab878 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 0 7 2 12
,I/CheckinTask( 2256): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2256): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,D/GCM     ( 1384): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  905): releaseWL(440ffbb8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2256): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d0a748 that was originally bound here
E/ActivityThread( 2256): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d0a748 that was originally bound here
E/ActivityThread( 2256): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2256): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2256): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2256): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2256): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2256): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2256): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2256): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2256): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2256): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2256): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2256): 	at bks.a(SourceFile:298)
E/ActivityThread( 2256): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2256): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2256): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2256): 	at java.lang.Thread.run(Thread.java:864)
I/GCM     ( 1384): GCM config loaded
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=100 [1][1][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-55 , oldRssi= -200
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,W/fb4a(:<default>):UserScope( 4434): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4434): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,E/fb4a(:<default>):LocalFbBroadcastManager( 4434): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =128f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4227e8a8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4227e8a8, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4242c998
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@42787c88
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  905): Going to sleep due to screen timeout...
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,W/PMS     (  905): mWirelessDisplayManager is null
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
,D/PMS     (  905): releaseWL(441ee290): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 370ms
D/NfcService( 1257): ScreenObserver: OFF
,D/NfcService( 1257): applyRouting - 0
,D/NfcService( 1257): applyRouting -2
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4366
D/PMS     (  905): acquireWL(42ed8018): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null,
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43bfc798)
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  905): wakingUp
D/PMS     (  905): releaseWL(42ed8018): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
I/WindowManager(  905): No lock screen! windowToken=null
D/PMN     (  905): onScreenOn
,D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): acquireWL(4333ac98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(4333ac98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/MtpService( 2448): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1257): applyRouting - 0
,D/MtpService( 2448): [MTP][onReceive]-
,D/AutoSetting( 1441): receiver - intent: android.intent.action.USER_PRESENT
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/NfcService( 1257): applyRouting -2
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19338 delay=15s
,D/AutoSetting( 1441): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/PMS     (  905): acquireWL(4276abf8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  905): releaseWL(4276abf8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): SET_SCREEN_ON:On
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1157): BG scan when screen On
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): Match BG scan, scan!
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WifiNative-wlan0(  905):    returned true
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1117): stop update clock
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
D/TetherSettings( 4139): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4139): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4139): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4139): Cust_ConnectToPC   : spcsc>false
D/        ( 4139): Cust_ConnectToPC   : IPT>true
,D/        ( 4139): Cust_ConnectToPC   : Singel_USB>false
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,W/Settings( 4139): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/SmartNS_Utility( 4139): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4139): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4139): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/PSReceiver( 4139): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4139): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4139): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4139):  defaultType:0
W/ContextImpl( 4139): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  905): updateScreenOn: false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4622 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1807): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1807): onScreenOn: 1452294322225
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1807): onScreenOn: 1452294322225
D/PMS     (  905): acquireWL(441be2e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1488 10028 null
D/PMS     (  905): releaseWL(441be2e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4242c998
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4242c998, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@42787c88
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(42731128): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,W/ContextImpl( 4622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/AlarmManager(  905): ACTION_SCREEN_OFF
,I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19338 mDataStallAlarmIntent=PendingIntent{4400bb70: PendingIntentRecord{42480cf0 android broadcastIntent}}
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
,D/SmartSyncUtils( 4622): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(436c7a90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4622 1000 null
D/PMS     (  905): acquireWL(4400dff0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,D/SmartSyncUtils( 4622): getMobilePolicyEnabled, result = true
D/PMS     (  905): releaseWL(436c7a90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/Process (  905): killProcessQuiet, pid=4255
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
,I/ActivityManager(  905): Killing 4255:com.google.android.apps.docs/u0a100 (adj 15): empty #17
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): SET_SCREEN_ON:Off
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1157): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4255
V/SRS_Proc(  370): ParamSet string: screen_state=off
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ContactMessageStore( 1246): start background delete task...
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
D/ContactMessageStore( 1246): size: 0 , 0
,D/ContactMessageStore( 1246): Background delete complete
D/NetworkPolicy(  905): updateScreenOn: false
D/PMS     (  905): releaseWL(4400dff0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4622): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4622): getMobilePolicyEnabled, result = true
,W/ContextImpl( 4622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4622): isEpsOn(), nState = 0
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42787c88
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42787c88, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42787c88, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42787c88
D/WifiService(  905): New client listening to asynchronous messages
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@427691f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@427691f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1807): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1807): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1807): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1807): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1807): onScreenOff
D/PMS     (  905): acquireWL(4337e998): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1488 10028 null
D/PMS     (  905): releaseWL(4337e998): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1441): service - mHandler: cancel location update
,D/AutoSetting( 1441): service -           changes count: 0
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{41da0f80 u0 com.test.thalitest/.MainActivity t2}
,I/GAV2    ( 4514): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  905): acquireWL(441e89a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1488 10028 null
,D/PMS     (  905): acquireWL(441e8908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1488 10028 null
,D/PMS     (  905): releaseWL(441e89a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  905): releaseWL(441e8908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/jxcore-log( 4366): Test app app.js loaded
I/jxcore-log( 4366): 
,I/Choreographer( 4366): Skipped 531 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4366): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4366): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41c27390 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  905): releaseWL(42731128): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4366): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1157): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=11 entropy=0
D/wpa_supplicant( 1157): Add randomness: count=12 entropy=1
D/wpa_supplicant( 1157): Add randomness: count=13 entropy=2
D/wpa_supplicant( 1157): Add randomness: count=14 entropy=3
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1157): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1157): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-5,5
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1157): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=15 entropy=4
D/wpa_supplicant( 1157): Add randomness: count=16 entropy=5
D/wpa_supplicant( 1157): Add randomness: count=17 entropy=6
D/wpa_supplicant( 1157): Add randomness: count=18 entropy=7
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1157): State: DISCONNECTED -> INACTIVE
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=,
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@426a4108 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@426a4108 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@426a4108 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1157): reply (489) for get BSS: id=0,
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000113911695
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
,I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000113911730
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
,I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000113911740
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=3
I/wpa_supplicant( 1157): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000113911720
,I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1157): ssid=01ABC
I/wpa_supplicant( 1157): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList,
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 113911695, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 113911730, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 113911740, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 113911720, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 4 to mScanResults
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/Process (  905): killProcessQuiet, pid=4279
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4279:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4279
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 10.989MB for 37010-byte allocation
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 11.017MB for 55510-byte allocation
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 11.034MB for 54588-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4434/10026)
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 11.110MB for 82904-byte allocation
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 11.117MB for 55828-byte allocation
,I/dalvikvm-heap( 4434): Grow heap (frag case) to 11.158MB for 72414-byte allocation
,D/libc    ( 4434): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4434): [NET] getaddrinfo-,err=8
D/libc    ( 4434): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4434): [NET] getaddrinfo-, 1
,D/libc    ( 4434): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6b7a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 13
D/libc    (  363): [NET]res_nsend:resplen=93
D/libc    (  363): [NET]res_queryN: exit 3, ancount=3
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4434): [NET] getaddrinfo_proxy-, success
,I/global  ( 4434): call createSocket() return a new socket.
D/libc    ( 4434): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4434): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4434): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4434): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(43a08a98): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4434 10026 null
,D/AutoSetting( 1501): service - handleMessage() stop self
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4434): I/O error closing connection
I/global  ( 4434): java.net.SocketException: Socket is closed
I/global  ( 4434): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4434): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4434): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4434): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4434): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4434): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4434): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4434): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4434): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4434): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4434): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4434): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4434): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4434): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4434): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4434): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4434): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4434): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4434): Removing a connection that never existed!
D/PMS     (  905): releaseWL(43a08a98): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{434122c0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  905): killProcessQuiet, pid=3879
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3879:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3879
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(43720f78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(43720f78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1157): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=19 entropy=8
D/wpa_supplicant( 1157): Add randomness: count=20 entropy=9
D/wpa_supplicant( 1157): Add randomness: count=21 entropy=10
D/wpa_supplicant( 1157): Add randomness: count=22 entropy=11
D/wpa_supplicant( 1157): Add randomness: count=23 entropy=12
D/wpa_supplicant( 1157): Add randomness: count=24 entropy=13
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1157): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1157): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 5: 64:,7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1157): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=25 entropy=14
D/wpa_supplicant( 1157): Add randomness: count=26 entropy=15
D/wpa_supplicant( 1157): Add randomness: count=27 entropy=16
D/wpa_supplicant( 1157): Add randomness: count=28 entropy=17
D/wpa_supplicant( 1157): Add randomness: count=29 entropy=18
D/wpa_supplicant( 1157): Add randomness: count=30 entropy=19
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1157): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1157): reply (783) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000132093588
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000132093625,
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000132093636
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=3
I/wpa_supplicant( 1157): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55,
I/wpa_supplicant( 1157): tsf=0000000113911720
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1157): ssid=01ABC
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000132093644
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC5999698
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=5
I/wpa_supplicant( 1157): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000132093655
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC4688432
I/wpa_supplicant( 1157): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 132093588, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 132093625, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 132093636, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 113911720, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 132093644, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 132093655, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1441): service - mHandler: update timezone
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1501): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1571): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1501): service - mHandler: update timezone
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1501): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1501): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1571): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1117): removeNotification.gc:53
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41d6e080 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 5 2 11
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(41c98db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{425054a0: PendingIntentRecord{42513e70 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140836, Int=0
D/PMS     (  905): acquireWL(42183d20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
V/AlarmManager(  905): sending alarm PendingIntent{42522908: PendingIntentRecord{4272cee0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141248, Int=0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1384/10028)
D/PMS     (  905): releaseWL(41c98db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  905): acquireWL(42615448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1384 10028 null
D/PMS     (  905): releaseWL(42615448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5a4e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/AutoSetting( 1441): service - handleMessage() stop self
,D/AutoSetting( 1441): service - onDestroy() END
,D/AutoSetting( 1441): service - handleMessage() quit looper
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): acquireWL(426fbd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(426fbd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): releaseWL(42183d20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/Process (  905): killProcessQuiet, pid=4242
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4242:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4242
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  905): acquireWL(42614e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41db0bc8: PendingIntentRecord{41d3f948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=148810, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42614e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1157): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1157): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=31 entropy=20
D/wpa_supplicant( 1157): Add randomness: count=32 entropy=21
D/wpa_supplicant( 1157): Add randomness: count=33 entropy=22
D/wpa_supplicant( 1157): Add randomness: count=34 entropy=23
D/wpa_supplicant( 1157): Add randomness: count=35 entropy=24
D/wpa_supplicant( 1157): Add randomness: count=36 entropy=25
D/wpa_supplicant( 1157): Add randomness: count=37 entropy=26
D/wpa_supplicant( 1157): Add randomness: count=38 entropy=27
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0,
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1157): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1157): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1157): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
,I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1157): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55,
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
,I/wpa_supplicant( 1157): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1157): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=39 entropy=28
D/wpa_supplicant( 1157): Add randomness: count=40 entropy=29
D/wpa_supplicant( 1157): Add randomness: count=41 entropy=30
D/wpa_supplicant( 1157): Add randomness: count=42 entropy=31,
D/wpa_supplicant( 1157): Add randomness: count=43 entropy=32
D/wpa_supplicant( 1157): Add randomness: count=44 entropy=33
D/wpa_supplicant( 1157): Add randomness: count=45 entropy=34
D/wpa_supplicant( 1157): Add randomness: count=46 entropy=35
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1157): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1157): reply (1073) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000150283074
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000150283113
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000150283124
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=3
I/wpa_supplicant( 1157): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000113911720
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1157): ssid=01ABC,
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000150283133
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC5999698
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=5
I/wpa_supplicant( 1157): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000150283143
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC4688432
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=6
I/wpa_supplicant( 1157): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000150283153
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=7
I/wpa_supplicant( 1157): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000150283170
I/wpa_supplicant( 1157): f
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 150283074, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 150283113, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 150283124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 113911720, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 150283133, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 150283143, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 150283153, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 150283170, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 8 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (8) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42e7c580 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1157): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1157): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=47 entropy=36
D/wpa_supplicant( 1157): Add randomness: count=48 entropy=37
D/wpa_supplicant( 1157): Add randomness: count=49 entropy=38
D/wpa_supplicant( 1157): Add randomness: count=50 entropy=39
D/wpa_supplicant( 1157): Add randomness: count=51 entropy=40
D/wpa_supplicant( 1157): Add randomness: count=52 entropy=41
D/wpa_supplicant( 1157): Add randomness: count=53 entropy=42
D/wpa_supplicant( 1157): Add randomness: count=54 entropy=43
D/wpa_supplicant( 1157): Add randomness: count=55 entropy=44
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wp,a_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1157): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1157): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 6: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1157): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1157): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=56 entropy=45
D/wpa_supplicant( 1157): Add randomness: count=57 entropy=46
D/wpa_supplicant( 1157): Add randomness: count=58 entropy=47
D/wpa_supplicant( 1157): Add randomness: count=59 entropy=48
D/wpa_supplicant( 1157): Add randomness: count=60 entropy=49
D/wpa_supplicant( 1157): Add randomness: count=61 entropy=50
D/wpa_supplicant( 1157): Add randomness: count=62 entropy=51
D/wpa_supplicant( 1157): Add randomness: count=63 entropy=52
D/wpa_supplicant( 1157): Add randomness: count=64 entropy=53
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1157): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1157): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000168503895
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000168503936
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000168503947
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=3
I/wpa_supplicant( 1157): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000113911720
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1157): ssid=01ABC
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000168503980
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC5999698
,I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=5
I/wpa_supplicant( 1157): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000168503970
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC4688432
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=6
I/wpa_supplicant( 1157): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000168503990
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=7
I/wpa_supplicant( 1157): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000168504000
I/wpa_supplicant( 1157): f
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 168503895, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 168503936, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 168503947, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 113911720, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 168503980, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 168503970, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 168503990, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 168504000, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): 8: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 168503955, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 9 to mScanResults
,V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (9) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/AutoSetting( 1501): service - handleMessage() stop self
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4296
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4296:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4296
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/TelephonyReceiver( 1246): switchBindHtcMsgCursor: null
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1157): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1157): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=65 entropy=54
D/wpa_supplicant( 1157): Add randomness: count=66 entropy=55
D/wpa_supplicant( 1157): Add randomness: count=67 entropy=56
D/wpa_supplicant( 1157): Add randomness: count=68 entropy=57
D/wpa_supplicant( 1157): Add randomness: count=69 entropy=58
D/wpa_supplicant( 1157): Add randomness: count=70 entropy=59
D/wpa_supplicant( 1157): Add randomness: count=71 entropy=60
D/wpa_supplicant( 1157): Add randomness: count=72 entropy=61
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1157): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 ,rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1157): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1157): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=73 entropy=62
D/wpa_supplicant( 1157): Add randomness: count=74 entropy=63
D/wpa_supplicant( 1157): Add randomness: count=75 entropy=64
D/wpa_supplicant( 1157): Add randomness: count=76 entropy=65
D/wpa_supplicant( 1157): Add randomness: count=77 entropy=66
D/wpa_supplicant( 1157): Add randomness: count=78 entropy=67
D/wpa_supplicant( 1157): Add randomness: count=79 entropy=68
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1157): Add randomness: count=80 entropy=69
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( ,1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1157): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1157): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000186711938
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000186711965
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000186711977
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=3
I/wpa_supplicant( 1157): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000113911720
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1157): ssid=01ABC
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000186712047
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC5999698
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=5
I/wpa_supplicant( 1157): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-87
I/wpa_supplicant( 1157): tsf=0000000186712036
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC4688432
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=6
I/wpa_supplicant( 1157): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000186712058
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=7
I/wpa_supplicant( 1157): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=000000018671206,8
I/wpa_supplicant( 1157): f
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 186711938, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 186711965, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 186711977, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 113911720, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 186712047, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 186712036, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  905): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 186712058, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 186712068, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 8: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 186712025, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 9 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList,
V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (9) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(425d5ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(425d5ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(444d2998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(444d2998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1157): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=81 entropy=70
D/wpa_supplicant( 1157): Add randomness: count=82 entropy=71
D/wpa_supplicant( 1157): Add randomness: count=83 entropy=72
D/wpa_supplicant( 1157): Add randomness: count=84 entropy=73
D/wpa_supplicant( 1157): Add randomness: count=85 entropy=74
D/wpa_supplicant( 1157): Add randomness: count=86 entropy=75
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1157): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 5: 06:7c:34:12:7f:81 s,sid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1157): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=87 entropy=76
D/wpa_supplicant( 1157): Add randomness: count=88 entropy=77
D/wpa_supplicant( 1157): Add randomness: count=89 entropy=78
D/wpa_supplicant( 1157): Add randomness: count=90 entropy=79
D/wpa_supplicant( 1157): Add randomness: count=91 entropy=80
D/wpa_supplicant( 1157): Add randomness: count=92 entropy=81
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1157): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1157): reply (1103) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220,
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000204893808
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000204893836
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000204893850
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000204893879
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC5999698
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=5
I/wpa_supplicant( 1157): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-87
I/wpa_supplicant( 1157): tsf=0000000204893869
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC4688432
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=6
I/wpa_supplicant( 1157): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000186712058,
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=7
I/wpa_supplicant( 1157): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000186712068
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC0990019
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=8
I/wpa_supplicant( 1157): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=243
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 204893808, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 204893836, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 204893850, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 204893879, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 204893869, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 186712058, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 186712068, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 204893859, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 8 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (8) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(44186380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41db0bc8: PendingIntentRecord{41d3f948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=208810, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44186380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1157): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=93 entropy=82
D/wpa_supplicant( 1157): Add randomness: count=94 entropy=83
D/wpa_supplicant( 1157): Add randomness: count=95 entropy=84
D/wpa_supplicant( 1157): Add randomness: count=96 entropy=85
D/wpa_supplicant( 1157): Add randomness: count=97 entropy=86
D/wpa_supplicant( 1157): Add randomness: count=98 entropy=87
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1157): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 5: 06:7c:34:12:7f:81 s,sid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1157): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=99 entropy=88
D/wpa_supplicant( 1157): Add randomness: count=100 entropy=89
D/wpa_supplicant( 1157): Add randomness: count=101 entropy=90
D/wpa_supplicant( 1157): Add randomness: count=102 entropy=91
D/wpa_supplicant( 1157): Add randomness: count=103 entropy=92
D/wpa_supplicant( 1157): Add randomness: count=104 entropy=93
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1157): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 ,target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1157): reply (813) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000223002574
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000223002599
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000223002611
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000223002640
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC5999698
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=5
I/wpa_supplicant( 1157): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-87
I/wpa_supplicant( 1157): tsf=0000000223002629
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC4688432
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=8
I/wpa_supplicant( 1157): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000223002620
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 223002574, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 223002599, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 223002611, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 223002640, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 223002629, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 223002620, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(436e9db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{43d3afa8: PendingIntentRecord{438997c8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227802, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4665 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{4267aa68: PendingIntentRecord{42510718 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452294431250, Int=10800000
,D/PMS     (  905): releaseWL(436e9db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4665/10047)
,D/Process (  905): killProcessQuiet, pid=4315
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4315:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4315
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,D/PMS     (  905): acquireWL(441e32c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{431fcef8: PendingIntentRecord{438997c8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231116, Int=0
,D/PMS     (  905): releaseWL(441e32c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1157): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=105 entropy=94
D/wpa_supplicant( 1157): Add randomness: count=106 entropy=95
D/wpa_supplicant( 1157): Add randomness: count=107 entropy=96
D/wpa_supplicant( 1157): Add randomness: count=108 entropy=97
D/wpa_supplicant( 1157): Add randomness: count=109 entropy=98
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
,I/wpa_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1157): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
,I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1157): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=110 entropy=99
D/wpa_supplicant( 1157): Add randomness: count=111 entropy=100
D/wpa_supplicant( 1157): Add randomness: count=112 entropy=101
,D/wpa_supplicant( 1157): Add randomness: count=113 entropy=102
D/wpa_supplicant( 1157): Add randomness: count=114 entropy=103
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): clear disabled list - type=1
,I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1157): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1157): reply (813) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000241183644
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000241183672
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000241183684,
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000241183703
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC5999698
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=5
I/wpa_supplicant( 1157): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-87
I/wpa_supplicant( 1157): tsf=0000000223002629
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC4688432
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=8
I/wpa_supplicant( 1157): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000241183693
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 241183644, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 241183672, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 241183684, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 241183703, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 223002629, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 241183693, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4397ed48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(4397ed48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1157): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=115 entropy=104
D/wpa_supplicant( 1157): Add randomness: count=116 entropy=105
D/wpa_supplicant( 1157): Add randomness: count=117 entropy=106
D/wpa_supplicant( 1157): Add randomness: count=118 entropy=107
D/wpa_supplicant( 1157): Add randomness: count=119 entropy=108
D/wpa_supplicant( 1157): Add randomness: count=120 entropy=109
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1157): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=2,4 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1157): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=121 entropy=110
D/wpa_supplicant( 1157): Add randomness: count=122 entropy=111
D/wpa_supplicant( 1157): Add randomness: count=123 entropy=112
D/wpa_supplicant( 1157): Add randomness: count=124 entropy=113
D/wpa_supplicant( 1157): Add randomness: count=125 entropy=114
D/wpa_supplicant( 1157): Add randomness: count=126 entropy=115
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1157): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1157): reply (809) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000259383846
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000259383874
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
,I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000259383886
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000259383907
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC5999698
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=8
I/wpa_supplicant( 1157): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000259383895
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=9
I/wpa_supplicant( 1157): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-90
I/wpa_supplicant( 1157): tsf=0000000259383917
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 259383846, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 259383874, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 259383886, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 259383907, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 259383895, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 259383917, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(440af5b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41db0bc8: PendingIntentRecord{41d3f948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=268810, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(440af5b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1157): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=127 entropy=116
D/wpa_supplicant( 1157): Add randomness: count=128 entropy=117
D/wpa_supplicant( 1157): Add randomness: count=129 entropy=118
D/wpa_supplicant( 1157): Add randomness: count=130 entropy=119
D/wpa_supplicant( 1157): Add randomness: count=131 entropy=120
D/wpa_supplicant( 1157): Add randomness: count=132 entropy=121
D/wpa_supplicant( 1157): Add randomness: count=133 entropy=122
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1157): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( ,1157): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1157): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=134 entropy=123
D/wpa_supplicant( 1157): Add randomness: count=135 entropy=124
D/wpa_supplicant( 1157): Add randomness: count=136 entropy=125
D/wpa_supplicant( 1157): Add randomness: count=137 entropy=126
D/wpa_supplicant( 1157): Add randomness: count=138 entropy=127
D/wpa_supplicant( 1157): Add randomness: count=139 entropy=128
D/wpa_supplicant( 1157): Add randomness: count=140 entropy=129
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1157): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.intern,al.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1157): reply (957) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000277473485
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000277473513
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000259383886
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-86
I/wpa_supplicant( 1157): tsf=0000000277473554
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC5999698
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=8
I/wpa_supplicant( 1157): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88
I/wpa_supplicant( 1157): tsf=0000000277473534
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=9
I/wpa_supplicant( 1157): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-90
I/wpa_supplicant( 1157): tsf=0000000277473544
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=10
I/wpa_supplicant( 1157): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-92
I/wpa_supplicant( 1157): tsf=0000000277473564
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC4688432
I/wpa_supplicant( 1157): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, c,apabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 277473485, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 277473513, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 259383886, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 277473554, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 277473534, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 277473544, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 277473564, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 7 to mScanResults
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1157): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1157): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=141 entropy=130
D/wpa_supplicant( 1157): Add randomness: count=142 entropy=131
D/wpa_supplicant( 1157): Add randomness: count=143 entropy=132
D/wpa_supplicant( 1157): Add randomness: count=144 entropy=133
D/wpa_supplicant( 1157): Add randomness: count=145 entropy=134
D/wpa_supplicant( 1157): Add randomness: count=146 entropy=135
D/wpa_supplicant( 1157): Add randomness: count=147 entropy=136
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 9
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 0
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1157): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 r,sn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 4: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 5: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1157): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1157): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1157): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1157): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1157): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1157): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=148 entropy=137
D/wpa_supplicant( 1157): Add randomness: count=149 entropy=138
D/wpa_supplicant( 1157): Add randomness: count=150 entropy=139
D/wpa_supplicant( 1157): Add randomness: count=151 entropy=140
D/wpa_supplicant( 1157): Add randomness: count=152 entropy=141
D/wpa_supplicant( 1157): Add randomness: count=153 entropy=142
D/wpa_supplicant( 1157): Add randomness: count=154 entropy=143
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): clear disabled list - type=1
I/wpa_supplicant( 1157): No suitable network found
W/wpa_supplicant( 1157): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1157): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1157): reply (1105) for get BSS: id=0,
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000295683654
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-55
I/wpa_supplicant( 1157): tsf=0000000295683682
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
,I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-78
I/wpa_supplicant( 1157): tsf=0000000295683694
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-86
I/wpa_supplicant( 1157): tsf=0000000295683705
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC5999698
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=8
I/wpa_supplicant( 1157): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-88,
I/wpa_supplicant( 1157): tsf=0000000277473534
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=9
I/wpa_supplicant( 1157): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
I/wpa_supplicant( 1157): level=-90
I/wpa_supplicant( 1157): tsf=0000000295683715
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=10
I/wpa_supplicant( 1157): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-92
I/wpa_supplicant( 1157): tsf=0000000295683724
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC4688432
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=11
I/wpa_supplicant( 1157): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1157): freq=2462
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 295683654, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 295683682, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 295683694, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 295683705, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 277473534, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 295683715, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 295683724, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 295683738, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 8 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (8) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/jxcore-log( 4366): --= Surplus to requirements =--
I/jxcore-log( 4366): 
I/jxcore-log( 4366): ****TEST TOOK:  ms ****
I/jxcore-log( 4366): 
,I/jxcore-log( 4366): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4366): 
,E/cutils-trace( 4687): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4687): ====startRecUseTime====
D/htc.customization.log.level( 4687):  is 
,W/CustomizationLogLevel( 4687): Level value is invalid, use default level 2
,D/CustomizationManager( 4687):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4687): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 4687): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4687): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4687): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4687): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4687): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4687): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4687): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4687): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4687): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4687): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4687): Parsing tag category name = system
,I/CustomizationCIDLoader( 4687): Parsing tag category name = application
I/CustomizationCIDLoader( 4687): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4687): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4687): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4687): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 4687): Parsing tag category name = Settings
D/CustomizationManager( 4687):  Read CID file spent 0.092 (s)
,D/CustomizationManager( 4687):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 4687): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4687): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4687): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4687): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4687, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4366
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  905): Killing 4366:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905):   Force finishing activity ActivityRecord{41da0f80 u0 com.test.thalitest/.MainActivity t2}
,W/PackageSettings(  905): Skipping PackageSetting{42384348 com.example.hello/10356} due to missing metadata
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1209): !!! FAILED BINDER TRANSACTION !!!
,W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4366 uid 10348
I/dalvikvm-heap( 4117): Grow heap (frag case) to 13.497MB for 1821008-byte allocation
,I/acms    ( 1884): Unregistering com.test.thalitest
E/acms    ( 1884): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1571): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,D/DotMatrix( 1571): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,W/GeofencerStateMachine( 1488): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1334): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1334): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): acquireWL(44195910): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1488 10028 null
D/PMS     (  905): releaseWL(44195910): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
,W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
W/InputDispatcher(  905): channel '4255f420 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '4255f420 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '4255f420 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
I/WindowState(  905): WIN DEATH: Window{4255f420 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/WindowManager(  905): WINDOW DIED Window{4255f420 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/AccTypeManager( 1334): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/Launcher( 1275): Deferring update until onResume
D/Launcher( 1275): waitUntilResume // bindAppsRemoved
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
,D/PackageBroadcastService( 2256): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4700 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/ExternalAccountType( 1334): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/ActivityManager(  905): Delaying start of: ServiceRecord{4416a7f0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
,I/MultiDex( 4700): install
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/MultiDex( 4700): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/MultiDex( 4700): loading existing secondary dex files
,I/MultiDex( 4700): load found 1 secondary dex files
,I/MultiDex( 4700): install done
,I/PeopleContactsSync( 2256): CP2 sync disabled
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2256, uid=10028, userID:0
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,D/PhoneApp( 1246): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4720 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/Icing   ( 2256): doRemovePackageData com.test.thalitest
,I/ProviderInstaller( 4700): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  905): acquireWL(42625c98): PARTIAL_WAKE_LOCK  Icing 0x1 2256 10028 null
,D/PMS     (  905): releaseWL(42625c98): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4720): install
,I/MultiDex( 4720): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4720): loading existing secondary dex files
,I/MultiDex( 4720): load found 1 secondary dex files
,I/MultiDex( 4720): install done
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ProviderInstaller( 4720): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/[PluginManager]RegisterService( 1441): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1441): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4329
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  905): Killing 4329:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  905): Recipient 4329
,I/IcingCorporaProvider( 2896): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4740 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4700): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4700): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4700): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4700): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4700): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4700): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4700): 	at ctn.run(SourceFile:985)
,W/dalvikvm( 4700): threadid=12: thread exiting with uncaught exception (group=0x417ebe30)
,E/AndroidRuntime( 4700): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4700): Process: com.google.android.gms.drive, PID: 4700
E/AndroidRuntime( 4700): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4700): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4700): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4700): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4700): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4700): 	at ctn.run(SourceFile:985)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
,E/SQLiteLog( 2896): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/Process ( 4700): killProcess, pid=4700
,E/SQLiteDBG( 2896): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63dce530
D/Process ( 4700): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,W/dalvikvm( 2896): threadid=16: thread exiting with uncaught exception (group=0x417ebe30)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
,E/AndroidRuntime( 2896): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2896): Process: com.google.android.googlequicksearchbox:search, PID: 2896
E/AndroidRuntime( 2896): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2896): 	at cid.d(PG:186)
E/AndroidRuntime( 2896): 	at clo.g(PG:594)
E/AndroidRuntime( 2896): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2896): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2896): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2896): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2896): 	at clr.tL(PG:827)
E/AndroidRuntime( 2896): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2896): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2896): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2896): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2896): killProcess, pid=2896
,D/Process ( 2896): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
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
I/ActivityManager(  905): Recipient 4700
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4700) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,W/PackageManager(  905): Unable to load service info ResolveInfo{42766e08 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2896
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2896): Died!
,D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2896) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/SQLiteDatabase( 4740): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4740): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4740): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4740): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4740): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4740): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4740): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4740): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4740): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4740): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4740): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4740): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4740): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4740): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4740): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4740): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4740): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4740): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4740): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4740): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4740): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4740): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4740): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4740): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4740): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4740): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4740): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4740): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4740): Couldn't open ClientFlag.db for writing (will try read-only):,
E/SQLiteOpenHelper( 4740): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4740): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221),
E/SQLiteOpenHelper( 4740): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4740): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4740): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4740): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
,E/SQLiteOpenHelper( 4740): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4740): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4740): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4740): 	,at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4740): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4740): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4740): 	at aGL.a(GellyInjectorStoreBase.java:136)
,E/SQLiteOpenHelper( 4740): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4740): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4740): 	at fx.a(GellyInjectorStore.java:95),
E/SQLiteOpenHelper( 4740): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4740): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4740): 	,at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4740): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4740): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4740): ,	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4740): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4740): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153),
E/SQLiteOpenHelper( 4740): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4740): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/SQLiteOpenHelper( 4740): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4740): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4740): 	at java.lang.reflect.Method.invokeNative(Native Method),
E/SQLiteOpenHelper( 4740): 	,at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4740): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4740): ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4740): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4740): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4740): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4740): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4740): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4740): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4740): ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4740): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4740): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
,E/SQLiteDatabase( 4740): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4740): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4740): 	,at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4740): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4740): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4740): threadid=11: thread exiting with uncaught exception (group=0x417ebe30)
,E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4740): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4740): Process: com.google.android.apps.docs, PID: 4740
E/AndroidRuntime( 4740): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4740): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4740): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4740): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4740): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4740): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4740): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4740): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4740): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4740): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4740): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4740): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4740): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4740): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
,E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
,D/Process ( 4740): killProcess, pid=4740
,D/Process ( 4740): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 ,
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4758 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  905): Recipient 4740
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4740) has died.
,W/ContextImpl( 4758): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4758): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4758): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4758): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4758): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4758): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4758): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4758): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4758): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4758): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4758): threadid=10: thread exiting with uncaught exception (group=0x417ebe30)
E/AndroidRuntime( 4758): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4758): Process: com.android.keychain, PID: 4758
E/AndroidRuntime( 4758): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4758): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4758): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4758): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4758): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4758): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4758): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4771 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4758): killProcess, pid=4758
,D/Process ( 4758): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452294510837.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  905): Recipient 4758
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.android.keychain (pid 4758) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10614ms
,D/AppTag  ( 4771): getInstance(Context context)
,D/AppTag  ( 4771): getInstance(Context context)
,D/AppTag  ( 4771): onCreate()
,D/PMS     (  905): acquireWL(43bab3a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4117 10160 null
,I/dalvikvm-heap( 4117): Grow heap (frag case) to 15.198MB for 1821008-byte allocation
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4789 uid=10098 gids={50098, 3003, 5012}
D/PMS     (  905): releaseWL(43bab3a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Process (  905): killProcessQuiet, pid=3989
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3989:com.google.android.gm/u0a107 (adj 15): empty #17
,I/dalvikvm-heap( 4117): Grow heap (frag case) to 16.934MB for 1821008-byte allocation
,I/DeviceManagement( 4789): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4789 dbg=false s=true
,I/DeviceManagement( 4789): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4789): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4789): WorkflowService: Starting workflow service
I/DeviceManagement( 4789): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c4bf60] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4789): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4789): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4789): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4789): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4803 uid=10099 gids={50099, 3003, 5012}
,I/ActivityManager(  905): Recipient 3989
,I/DeviceManagement( 4789): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 4789): SessionStateController: Checking invariants...
,D/Documents( 4803): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4803): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4803): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4803): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4803): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4803): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4803): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4803): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4803): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4803): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4803): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4803): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4803): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4803): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4803): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4803): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4803): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4803): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4803): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4803): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4803): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4803): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4803): threadid=1: thread exiting with uncaught exception (group=0x417ebe30)
,E/AndroidRuntime( 4803): FATAL EXCEPTION: main
E/AndroidRuntime( 4803): Process: com.android.documentsui, PID: 4803
E/AndroidRuntime( 4803): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4803): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4803): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4803): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4803): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4803): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4803): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4803): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4803): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4803): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4803): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4803): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4803): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4803): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4803): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4803): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4803): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4803): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4803): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4803): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4803): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4803): 	... 10 more
,I/ActivityManager(  905): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4817 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  905): killProcessQuiet, pid=4408
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Killing 4408:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,E/ActivityManager(  905): App crashed! Process: com.android.documentsui
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/GCM     ( 1384): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452294511207.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  905): Recipient 4408
,D/Process (  905): killProcessQuiet, pid=3857
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Killing 3857:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/Process ( 4803): killProcess, pid=4803
,D/Process ( 4803): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/GCM     ( 1384): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  905): Recipient 4803
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.documentsui (pid 4803) has died.
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/ExternalStorage( 4817): After updating volumes, found 1 active roots
,E/SQLiteDatabase( 4789): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4789): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4789): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4789): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4789): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4789): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4789): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4789): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4789): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4789): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4789): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4789): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4789): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4789): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4789): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4789): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4789): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4789): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4789): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4789): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4789): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4833 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4789): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4789): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4789): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4789): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4789): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4789): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4789): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4789): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4789): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4789): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4789): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4789): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4789): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4789): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c4bf60]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4789): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4789): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4789): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4789): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4789): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4789): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4789): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4789): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4789): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4789): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4789): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4789): WorkflowService: Stopping workflow service
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41caedd0 +
I/Prism.WidgetManager( 1275): onLoadItems() +
,I/ActivityManager(  905): Recipient 3857
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  905): Client com.google.android.music (pid 3857): Died!
,E/SQLiteDatabase( 4833): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4833): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4833): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4833): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4833): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4833): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4833): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4833): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4833): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4833): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4833): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4833): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4833): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4833): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4833): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4833): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4833): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4833): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4833): Opened MyDB.db in read-only mode
,D/Process (  905): killProcessQuiet, pid=4463
,I/ActivityManager(  905): Killing 4463:com.google.android.setupwizard/u0a78 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4463
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0

```
