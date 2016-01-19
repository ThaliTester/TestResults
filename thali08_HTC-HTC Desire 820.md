#### Test 564317025f150b2_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,--------- beginning of /dev/log/main
I/SensorManager(  907): mEventCount = 1200
E/cutils-trace( 4517): Error opening trace file: No such file or directory (2)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/CustomizationManager( 4517): ====startRecUseTime====
D/htc.customization.log.level( 4517):  is 
W/CustomizationLogLevel( 4517): Level value is invalid, use default level 2
D/CustomizationManager( 4517):  Read ACC file spent 0.079 (s)
D/CIDMapFileReader( 4517): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4517): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4517): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4517): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4517): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4517): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4517): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4517): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4517): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4517): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4517): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4517): Parsing tag category name = system
I/CustomizationCIDLoader( 4517): Parsing tag category name = application
I/CustomizationCIDLoader( 4517): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4517): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4517): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4517): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4517): Parsing tag category name = Settings
D/CustomizationManager( 4517):  Read CID file spent 0.127 (s)
D/CustomizationManager( 4517):  All configurations done spent 0.127 (s)
W/HtcNativeFlag( 4517): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4517): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4517): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4517): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4517
D/PMS     (  907): acquireHCC(424471d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(4245f610): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x626c6728 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1131807064
D/PMS     (  907): acquireWL(42470238): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bf4d48
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4528 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4528): Copying FileAsset 0x5c752428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4528): Binding Chromium to main looper Looper (main, tid 1) {41ad4600}
I/LibraryLoader( 4528): Expected native library version number "",actual native library version number ""
I/chromium( 4528): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4528): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(43b05b48): PARTIAL_WAKE_LOCK  AudioMix 0x1 365 1013 null
D/PMS     (  907): acquireWL(42453700): PARTIAL_WAKE_LOCK  AudioMix 0x1 365 1013 null
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43dab098:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  907): releaseWL(43b05b48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4528): 1101963320: getState(). Returning 12
I/Adreno-EGL( 4528): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4528): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4528): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4528): Local Branch: 
I/Adreno-EGL( 4528): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4528): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4528):                  aa63bbd948f41d15fc72f585e
W/chromium( 4528): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4528): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4528): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4528): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4528): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4528): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4528): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4528): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4528): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4528): CordovaWebView is running on device made by: HTC
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/AwContents( 4528): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1270
W/ResourceType( 4528): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4528): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b1b6e8, mServedView=org.apache.cordova.engine.SystemWebView{41ae1350 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=4528
W/XT9_C   ( 1205): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1205): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4528): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +298ms
D/PMS     (  907): releaseWL(42470238): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4528): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4528): JniHelper::setJavaVM(0x415a9048), pthread_self() = 1662898208
D/JX-Cordova( 4528): jxcore cordova android initializing
I/io.jxcore.node.ConnectionHelper( 4528): Build version SDK_INT: 19
I/ActivityManager(  907): Waited long enough for: ServiceRecord{444f2938 u0 com.htc.htclocationservice/.AutoSettingService}
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 12.033MB for 63974-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 12.088MB for 95956-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 12.171MB for 143930-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 12.287MB for 215890-byte allocation
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 12.456MB for 323830-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 13.112MB for 728606-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 13.708MB for 1092904-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 14.627MB for 1639352-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 15.939MB for 2459024-byte allocation
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 18.061MB for 3688532-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
,W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
D/PMS     (  907): releaseHCC(424471d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(4245f610): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4528): Initializing JXcore engine
,W/jxcore-log( 4528): JXcore engine is ready
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 4528): Starting JXcore engine
,W/jxcore-log( 4528): Platform android
W/jxcore-log( 4528): 
,W/jxcore-log( 4528): Process ARCH arm
W/jxcore-log( 4528): 
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4572 uid=10077 gids={50077}
,D/PMS     (  907): acquireWL(4233af90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
,V/AlarmManager(  907): sending alarm PendingIntent{41ec1cc8: PendingIntentRecord{4246e8a8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453190756953, Int=60000
,D/PMS     (  907): releaseWL(4233af90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4572): SMSBackupAgentService started
,D/SMSBackup( 4572): Checking restore status
,D/SMSBackup( 4572): Restore complete
,D/SMSBackup( 4572): cancelCheckAlarm
,D/SMSBackup( 4572): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  907): killProcessQuiet, pid=3183
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3183:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3183
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): releaseWL(42453700): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4528): JXcore Cordova bridge is ready!
I/jxcore-log( 4528): 
,W/jxcore-log( 4528): JXcore engine is started
,I/chromium( 4528): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4528): Toggling radios to true
I/jxcore-log( 4528): 
,D/BluetoothAdapter( 4528): enable(): BT is already enabled..!
,D/WifiManager( 4528): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4528, uid=10189
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
,W/Settings:Agent(  907): Process.myTid(): 1269
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	,at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	,at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	,at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): ,
W/Settings:Agent(  907): << traceCallingStack(): 3(ms)
D/WifiManager( 4528): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
D/WifiManager( 4528): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): TDLS: Tear down peers,
I/wpa_supplicant( 1175): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4528): Radios toggled
I/jxcore-log( 4528): 
I/jxcore-log( 4528): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4528): 
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 48
,I/wpa_supplicant( 1175): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1175): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1175): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7071bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1175):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1175): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
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
,D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1175): EAPOL: External notification - portValid=0
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
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(43746588): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): Fast associate: Old scan results
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 1175): wpa_supplicant_scan enter
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1175): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20374 mDataStallAlarmIntent=PendingIntent{42273178: PendingIntentRecord{4206e130 android broadcastIntent}}
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4255): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  358): [NET] entry_id:7   entry:0xb79bf6f0  removed 
D/libc    (  358): [NET] entry_id:9   entry:0xb79bfcc0  removed 
D/libc    (  358): [NET] entry_id:5   entry:0xb79bf818  removed 
D/libc    (  358): [NET] entry_id:8   entry:0xb79bed90  removed 
D/libc    (  358): [NET] entry_id:6   entry:0xb79bf1d0  removed 
D/libc    (  358): [NET] entry_id:4   entry:0xb79befd8  removed 
D/libc    (  358): [NET] entry_id:2   entry:0xb79bf108  removed 
D/libc    (  358): [NET] entry_id:10   entry:0xb79bfd78  removed 
D/libc    (  358): [NET] entry_id:3   entry:0xb79bf2e0  removed 
D/libc    (  358): [NET] entry_id:1   entry:0xb79bf410  removed 
D/libc    (  358): [NET] entry_id:11   entry:0xb79bfe30  removed 
,D/libc    (  358): *************************
D/libc    (  358): *** DNS CACHE FLUSHED ***
D/libc    (  358): *************************
,D/WISPrService( 4255): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiService(  907): New client listening to asynchronous messages
D/PMS     (  907): acquireWL(4373da80): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1397 10028 null
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
,D/WISPrService( 4255): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4255): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(425892f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
,D/PMS     (  907): acquireWL(44315fc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1397 10028 null
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  907):    returned false
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1397/10028)
D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  907): releaseWL(44315fc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  907): releaseWL(4373da80): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
I//system/bin/ip(  358): RTNETLINK answers: No such process
,I/logwrapper(  358): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/PMS     (  907): releaseWL(425892f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,D/PMS     (  907): acquireWL(4424e1b0): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  907): releaseWL(4424e1b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42eb6210): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  907): releaseWL(42eb6210): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(44255220): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  907): releaseWL(44255220): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(43b5afd8): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  907): releaseWL(43b5afd8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,I/NetworkMonitor( 3928): type=WIFI subType= reason=null isConnected=false
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/Tethering(  907): No IPv4 upstream interface, giving up.
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4415/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1454/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3928/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1878/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4415/10100)
D/PMS     (  907): acquireWL(425bab30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1993/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4597 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  907): releaseWL(425bab30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4597): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4597): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4597): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4597): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
V/DexLibLoader( 4597): Preparing secondary program dexes.
V/DexLibLoader( 4597): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4597): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4597): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4597): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4597): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4597): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4597): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4597): Dex already copied
D/OdexVerifier( 4597): Odex verification is skipped.
V/DexLibLoader( 4597): Creating class loader
V/DexLibLoader( 4597): Finished creating class loader
V/DexLibLoader( 4597): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4597): Dex already copied
D/OdexVerifier( 4597): Odex verification is skipped.
V/DexLibLoader( 4597): Creating class loader
V/DexLibLoader( 4597): Finished creating class loader
V/DexLibLoader( 4597): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4597): Dex already copied
D/OdexVerifier( 4597): Odex verification is skipped.
V/DexLibLoader( 4597): Creating class loader
V/DexLibLoader( 4597): Finished creating class loader
V/DexLibLoader( 4597): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4597): Dex already copied
D/OdexVerifier( 4597): Odex verification is skipped.
V/DexLibLoader( 4597): Creating class loader
V/DexLibLoader( 4597): Finished creating class loader
V/DexLibLoader( 4597): Verifying classes from secondary dexes.
,D/DexLibLoader( 4597): DexLibLoader.ensureDexLoaded took 21 ms
,W/dalvikvm( 4597): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4597): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4597): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4597): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4597): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4597): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4597): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/PMS     (  907): acquireWL(43b7a860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41acb890: PendingIntentRecord{42359d68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=107788, Int=0
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1175): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1175): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1175): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1175): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
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
D/wpa_supplicant( 1175): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb70734e8  current_ssid=0x0
D/wpa_supplicant( 1175): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1175): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1175): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1175): check if in concurrent case
I/wpa_supplicant( 1175): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  907): [MLHD] enter handleMedi,aLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1175): RSN: PMKSA cache search - network_ctx=0xb70734e8 try_opportunistic=0
D/wpa_supplicant( 1175): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1175): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1175): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1175): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1175): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1175): nl80211: Unsubscribe mgmt frames handle 0xb7072718 (mode change)
D/wpa_supplicant( 1175): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7072718
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb7072718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb7072718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb7072718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb7072718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb7072718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb7072718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb7072718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb7072718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb7072718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb7072718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
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
,D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1175): reply (489) for get BSS: id=0
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000107791160
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-53
I/wpa_supplicant( 1175): tsf=0000000107791178
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2427
I/wpa_supplicant( 1175): level=-79
I/wpa_supplicant( 1175): tsf=0000000107791182
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-54
I/wpa_supplicant( 1175): tsf=0000000107791174
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 107791160, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 107791178, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 107791182, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 107791174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(43b7a860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/dalvikvm( 4597): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/ClockThread( 1115): now=1453190760052 next=59948
,W/dalvikvm( 4597): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1175): nl80211: Connect event
D/wpa_supplicant( 1175): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1175): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1175): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1175): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1175): TDLS: Remove peers on association
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1175): EAPOL: enable timer tick
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1175): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1175): Get randomness: len=32 entropy=5
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  907): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1175): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb70729f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1175):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 11
D/Tethering(  907): interfaceStatusChanged wlan0, true
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1175): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6efbb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 1175):    broadcast key
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1175): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1175): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1175): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
E/wpa_supplicant( 1175): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=6
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
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1175): EAPOL authentication completed successfully
I/wpa_supplicant( 1175): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
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
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4255): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4255): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/FbInjectorInitializer( 4597): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 1
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null,
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(43b4a7b8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiP2pService(  907): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42572408 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42572408 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4597): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4597): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4597): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=3640
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3640:com.htc.task/u0a70 (adj 15): empty #17
,D/PMS     (  907): acquireWL(442038a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3640
,D/PMS     (  907): acquireWL(4258e1c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1223 10028 null
,D/PMS     (  907): releaseWL(442038a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/PMS     (  907): releaseWL(4258e1c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1397): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/AutoSetting( 1383): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4626 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1383/10053)
,D/AutoSetting( 1383): Util - no network available!
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1383/10053)
D/AutoSetting( 1383): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1383): service - mHandler: cancel location update
D/AutoSetting( 1383): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4597): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4597): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4597): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4626): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4626): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4626): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4626): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4640 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4335
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4335:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4626/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4626/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4626/10078)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4597): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/Process (  907): killProcessQuiet, pid=4355
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4657 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 4355:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4355
,D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Recipient 4335
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 9.958MB for 84664-byte allocation
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 9.976MB for 28144-byte allocation
E/dalvikvm( 4597): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4597): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4597): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4597): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4597): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4597): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4597): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4597): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4597): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4597): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4597): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4597): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4597): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4597): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4597): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4597): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4597): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4597): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 10.017MB for 39954-byte allocation
,I/SensorManager(  907): mEventCount = 1350
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 10.093MB for 79892-byte allocation
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4657): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4657): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4657): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4657): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4657): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  907): releaseWL(43b4a7b8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
I/dalvikvm-heap( 4597): Grow heap (frag case) to 10.280MB for 75760-byte allocation
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -53, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42541670 u0 ReceiverList{43b25cb0 4597 com.facebook.katana/10026/u0 remote:422d0ae0}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42541670 u0 ReceiverList{43b25cb0 4597 com.facebook.katana/10026/u0 remote:422d0ae0}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425373e0 u0 ReceiverList{43b200c8 4597 com.facebook.katana/10026/u0 remote:42195c28}}
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20376 delay=15s
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  907): WAN detection
,D/WISPrService( 4255): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1115): WifiActivity: 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/MDST    (  907): default: setTeardownRequested(true)
,D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@424036c8
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  358): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4657/10151)
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(4245f610): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4626/10078)
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:0
,D/PMS     (  907): acquireWL(424583a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
V/WebViewChromiumFactoryProvider( 4657): Binding Chromium to main looper Looper (main, tid 1) {41ad9028}
I/LibraryLoader( 4657): Expected native library version number "",actual native library version number ""
I/chromium( 4657): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4657): Initializing chromium process, renderers=0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(4249d558): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1223 10028 null
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/wpa_supplicant( 1175): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1175): EAPOL: disable timer tick
D/PMS     (  907): acquireWL(43b4ebe0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1454 10028 null
D/PMS     (  907): releaseWL(4245f610): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  907): releaseWL(424583a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I//system/bin/ip(  358): RTNETLINK answers: No such file or directory
,I/logwrapper(  358): /system/bin/ip terminated by exit(254)
D/PMS     (  907): releaseWL(43b4ebe0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,I/CheckinService( 1223): Preparing to send checkin request
,I/EventLogService( 1223): Accumulating logs since 1453190710300
D/PMS     (  907): acquireWL(42492578): PARTIAL_WAKE_LOCK  AudioMix 0x1 365 1013 null
D/PMS     (  907): acquireWL(4259af20): PARTIAL_WAKE_LOCK  AudioMix 0x1 365 1013 null
,D/PMS     (  907): releaseWL(42492578): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/AudioManagerAndroid( 4657): BLUETOOTH permission is missing!
I//system/bin/ip(  358): RTNETLINK answers: No such process
I/logwrapper(  358): /system/bin/ip terminated by exit(2)
,I/Adreno-EGL( 4657): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4657): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4657): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4657): Local Branch: 
I/Adreno-EGL( 4657): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4657): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4657):                  aa63bbd948f41d15fc72f585e
,I/GoogleHttpClient( 1223): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1223): Using GMS GoogleHttpClient
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/GCoreFlp( 1454): Unknown pending intent to remove.
D/PMS     (  907): acquireWL(42fbd100): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1454 10028 null
D/PMS     (  907): releaseWL(42fbd100): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NSApplication( 4657): Starting up...
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1223/10028)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1223/10028)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4657/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4657/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=4067
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4233/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4233/10160)
I/ActivityManager(  907): Killing 4067:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,D/GCM     ( 1397): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/GLSUser ( 1397): GoogleAccountDataService.getToken()
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,W/GLSActivity( 1397): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1397): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1397): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  907): Recipient 4067
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/CheckinRequestBuilder( 1223): awaiting user notification for token
D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b97200 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 6 2 12
,I/jxcore-log( 4528): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4528): 
I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4734 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4734): install
,I/MultiDex( 4734): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4734): loading existing secondary dex files
,I/MultiDex( 4734): load found 1 secondary dex files
,I/MultiDex( 4734): install done
,I/ProviderInstaller( 4734): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1397): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4734): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4734): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4734): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4734): Local Branch: 
I/Adreno-EGL( 4734): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4734): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4734):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4734): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4734): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4734): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4734): Local Branch: 
I/Adreno-EGL( 4734): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4734): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4734):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4528): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4528): 
,I/jxcore-log( 4528): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4528): 
,I/jxcore-log( 4528): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4528): 
,I/jxcore-log( 4528): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4528): 
,I/jxcore-log( 4528): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4528): 
,I/jxcore-log( 4528): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4528): 
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4734/10028)
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): releaseWL(43746588): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,I/NetworkMonitor( 3928): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3928/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4626/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1454/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4415/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1454/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
I/acms    ( 1878): Checking Certificates
I/acms    ( 1878): Checking Developer Certificates
I/acms    ( 1878): Checking Application Certificates
I/acms    ( 1878): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1878): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1878): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
I/acms    ( 1878): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3963/10051)
D/PMS     (  907): acquireWL(425cf508): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4263e6c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1878/1000)
I/acms    ( 1878): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1878): Updating next query delay: 75600000
I/mlserverapp( 1878): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1878): cancelACMSProgrammedChecks
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4415/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1993/10021)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
D/PMS     (  907): acquireWL(445abf40): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1327): Unsupported attribute readOnly
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4757 uid=10106 gids={50106, 3003, 5012}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(4263e6c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/PMS     (  907): acquireWL(43ba8f10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
D/PMS     (  907): releaseWL(425cf508): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  907): releaseWL(43ba8f10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1397): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
,D/PMS     (  907): acquireWL(43a73570): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1397 10028 null
D/libc    ( 1397): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1397): [NET] getaddrinfo-,err=8
D/libc    ( 1397): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1397): [NET] getaddrinfo-, 1
D/libc    ( 1397): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =4e +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  358): [NET] NOT IN CACHE
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4597): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/AutoSetting( 1383): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/MobileConnectivityChangeReceiver( 4626): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4626): onReceive CONNECTIVITY_CHANGE networkType=1
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1383/10053)
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4597): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4657/10151)
,D/AutoSetting( 1383): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1383): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1383): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1383): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1383): service - handleMessage() setting current location null
D/AutoSetting( 1383): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1383): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1383/10053)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4233/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4233/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 192
D/libc    (  358): [NET]res_nsend:resplen=79
D/libc    (  358): [NET]res_queryN: exit 3, ancount=2
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1397): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4233): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
,D/libc    ( 1397): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1397): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
,I/NewsWeather( 4757): LocationClient connecting
D/PMS     (  907): acquireWL(43ba0ee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1397 10028 null
D/PMS     (  907): releaseWL(43ba0ee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4734): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4734): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4734): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4734): Local Branch: 
I/Adreno-EGL( 4734): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4734): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4734):                  aa63bbd948f41d15fc72f585e
,I/NewsWeather( 4757): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4757): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4757): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4757): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4757): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4757): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,W/Settings( 4734): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinTask( 1223): Sending checkin request (8969 bytes)
D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =168 +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE
,D/GCM     ( 1397): Connected
D/PMS     (  907): acquireWL(44457f28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1397 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/PMS     (  907): releaseWL(43a73570): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 247
D/libc    (  358): [NET]res_nsend:resplen=84
,D/libc    (  358): [NET]res_queryN: exit 3, ancount=2
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1397/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/PMS     (  907): releaseWL(44457f28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): acquireWL(4256ba88): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1397 10028 null
,I/ProviderInstaller( 4757): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1397): Message class mpf
I/NewsWeather( 4757): Last usage 0, idle 1453190762s, sync interval 2592000s
,I/NewsWeather( 4757): setPeriodicSync in seconds 2592000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43b38800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1397/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  907): releaseWL(43b38800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4757): onConnected null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1397/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
,W/GCoreFlp( 1454): No location to return for getLastLocation()
,I/NewsWeather( 4757): LocationClient onConnected: location null
D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/PMS     (  907): acquireWL(43ac2fc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1454 10028 null
D/PMS     (  907): releaseWL(4256ba88): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): acquireWL(4421e678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1397 10028 null
D/PMS     (  907): acquireWL(44420500): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1454 10028 null
D/PMS     (  907): releaseWL(43ac2fc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  907): releaseWL(4421e678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  907): releaseWL(44420500): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4757): Skip sync for lookup editions
,I/NewsWeather( 4757): syncNewsAppData traffic type BACKGROUND_POLL
,I/jxcore-log( 4528): Test app app.js loaded
I/jxcore-log( 4528): 
,I/NewsWeather( 4757): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,I/Choreographer( 4528): Skipped 290 frames!  The application may be doing too much work on its main thread.
,W/GLSUser ( 1397): GoogleAccountDataService.getToken()
,I/chromium( 4528): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/GLSActivity( 1397): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1397): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1397): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/NewsWeather( 4757): Unrecoverable authentication exception
E/NewsWeather( 4757): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4757): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4757): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4757): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41bfde90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 7 2 12
,D/libc    ( 4757): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4757): [NET] getaddrinfo-,err=8
D/libc    ( 4757): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4757): [NET] getaddrinfo-, 1
,D/libc    ( 4757): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =8db3 +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE
,D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  358): [NET]res_nsend:resplen=70
,D/libc    (  358): [NET]res_queryN: exit 3, ancount=2
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4757): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4757): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4757): [NET] getaddrinfo-,err=8
,W/dalvikvm( 4528): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4528): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4528): BLE advertisement is supported
I/jxcore-log( 4528): 
,D/PMS     (  907): acquireWL(42e23088): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1397 10028 null
,D/PMS     (  907): releaseWL(42e23088): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1223/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=10 [30][3][0]
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1223/10028)
,D/PMS     (  907): acquireWL(43b5eec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1397 10028 null
,E/NewsWeather( 4757): Failed to syncNewsAppData
,E/NewsWeather( 4757): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(43b5eec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
,D/PMS     (  907): acquireWL(42cb47b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 69856, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(445abf40): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/Process (  907): killProcessQuiet, pid=4384
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Killing 4384:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1454/10028)
D/PMS     (  907): releaseWL(42cb47b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(440106f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1397): GoogleAccountDataService.getToken()
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  907): releaseWL(440106f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  907): Recipient 4384
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSActivity( 1397): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1397): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1397): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 1223): awaiting user notification for token
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41eacba8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 7 2 12
,I/CheckinTask( 1223): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1223): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/GCM     ( 1397): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  907): releaseWL(4249d558): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1223): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bae5a0 that was originally bound here
E/ActivityThread( 1223): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bae5a0 that was originally bound here
E/ActivityThread( 1223): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1223): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1223): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1223): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1223): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1223): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1223): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1223): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1223): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1223): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1223): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1223): 	at bks.a(SourceFile:298)
E/ActivityThread( 1223): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1223): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1223): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1397): GCM config loaded
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-53 , oldRssi= -200
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,W/fb4a(:<default>):UserScope( 4597): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4597): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4597): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-,err=8
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
,D/libc    (  358): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =1d4a +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE
,D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  358): [NET]res_nsend:resplen=172
,D/libc    (  358): [NET]res_queryN: exit 3, ancount=4
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,D/PMS     (  907): releaseWL(4259af20): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42130438
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42130438, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42269290
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@42619cd8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 374ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/NfcService( 1251): ScreenObserver: OFF
,D/NfcService( 1251): applyRouting - 0
W/ResourceType( 4528): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4528): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41ae1350 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/NfcService( 1251): applyRouting -2
I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42f80e88)
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
D/HABCtrl (  907): TPE algorithm. remove timeout.
I/InputMethodManagerService(  907): Disable input method client, pid=4528
D/PMS     (  907): OOBE c monitor 11
D/PMS     (  907): acquireWL(42ceee68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/PMS     (  907): releaseWL(42ceee68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  907): wakingUp
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
I/WindowManager(  907): No lock screen! windowToken=null
D/PMS     (  907): acquireWL(4316ae60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(4316ae60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  907): onScreenOn
,D/MtpService( 1993): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1251): applyRouting - 0
,D/MtpService( 1993): [MTP][onReceive]-
,D/NfcService( 1251): applyRouting -2
,D/AutoSetting( 1383): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  907): acquireWL(43b22e10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/PMS     (  907): releaseWL(43b22e10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/TetherSettings( 4255): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4255): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4255): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4255): Cust_ConnectToPC   : spcsc>false
D/        ( 4255): Cust_ConnectToPC   : IPT>true
D/        ( 4255): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4255): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4255): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4255): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4255): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1383): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/PSReceiver( 4255): onReceive:android.intent.action.USER_PRESENT
,I/ClockThread( 1115): stop update clock
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
,I/SmartNS_PSService( 4255): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4255): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4255):  defaultType:0
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
W/ContextImpl( 4255): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20377 delay=15s
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
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
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=25 [4][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97,
D/WIFI_ICON( 1115): WifiActivity: 0
,D/WifiNative-wlan0(  907):    returned true
,V/SRS_Proc(  365): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4802 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/NetworkPolicy(  907): updateScreenOn: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4802): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1794): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): onScreenOn: 1453190765410
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1794): onScreenOn: 1453190765411
D/PMS     (  907): acquireWL(43d02bc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1454 10028 null
D/PMS     (  907): releaseWL(43d02bc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/SmartSyncUtils( 4802): isEpsOn(), nState = 0
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42269290
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
D/PMS     (  907): acquireWL(42e983e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4802 1000 null
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42269290, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@42619cd8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(4308cb28): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42e983e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  907): releaseWL(4308cb28): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20377 mDataStallAlarmIntent=PendingIntent{41da3588: PendingIntentRecord{437a6640 android broadcastIntent}}
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): SET_SCREEN_ON:Off
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1175): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1175): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(44411110): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
V/SRS_Proc(  365): ParamSet string: screen_state=off
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/ContactMessageStore( 1241): start background delete task...
,D/SmartSyncUtils( 4802): getMobilePolicyEnabled, result = true
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
D/NetworkPolicy(  907): updateScreenOn: false
,D/Process (  907): killProcessQuiet, pid=4415
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/ActivityManager(  907): Killing 4415:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/PMS     (  907): releaseWL(44411110): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4802): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4802): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4802): isEpsOn(), nState = 0
W/ContextImpl( 4802): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42619cd8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42619cd8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42619cd8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:,
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42619cd8
D/WifiService(  907): New client listening to asynchronous messages
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425df8f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425df8f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] getTotalRam: 1873 Mb
,D/AutoSetting( 1383): service - mHandler: cancel location update
,D/AutoSetting( 1383): service -           changes count: 0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1794): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1794): onScreenOff
D/PMS     (  907): acquireWL(42f98960): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1454 10028 null
D/PMS     (  907): releaseWL(42f98960): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  907): Recipient 4415
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4657): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4757): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  907): killProcessQuiet, pid=4438
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4438:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4438
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1500): service - handleMessage() stop self
,D/AutoSetting( 1500): service - onDestroy() END
,D/AutoSetting( 1500): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4402
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4402:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4402
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 10.994MB for 37000-byte allocation
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 11.023MB for 55496-byte allocation
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 11.040MB for 54552-byte allocation
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 11.106MB for 82850-byte allocation
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 11.113MB for 55792-byte allocation
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 11.153MB for 72362-byte allocation
,D/libc    ( 4597): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4597): [NET] getaddrinfo-,err=8
D/libc    ( 4597): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4597): [NET] getaddrinfo-, 1
,D/libc    ( 4597): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =cd96 +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE
,D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 28
D/libc    (  358): [NET]res_nsend:resplen=93
D/libc    (  358): [NET]res_queryN: exit 3, ancount=3
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4597): [NET] getaddrinfo_proxy-, success
I/global  ( 4597): call createSocket() return a new socket.
D/libc    ( 4597): [NET] getaddrinfo+,hn 13(0x3137392e36302e),sn(),family 0,flags 4
,D/libc    ( 4597): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4597): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4597): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(4446e488): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4597 10026 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 11.211MB for 85864-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 11.216MB for 85922-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4597/10026)
,I/global  ( 4597): I/O error closing connection
I/global  ( 4597): java.net.SocketException: Socket is closed
I/global  ( 4597): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4597): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4597): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4597): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4597): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4597): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4597): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4597): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4597): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4597): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4597): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4597): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4597): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4597): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4597): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4597): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4597): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4597): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4597): Removing a connection that never existed!
D/PMS     (  907): releaseWL(4446e488): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(441fc6d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db23a0: PendingIntentRecord{42475f60 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=132088, Int=0
,D/PMS     (  907): acquireWL(441fc188): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(441fc6d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43eda628): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(441fc188): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(43eda628): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/PMS     (  907): acquireWL(43b167d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b167d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1383): service - mHandler: update timezone
,D/AutoSetting( 1500): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1500): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1500): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1500): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1500): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1561): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1500): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1500): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1500): service - mHandler: update timezone
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1500): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1500): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1500): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1500): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1115): removeNotification.gc:54
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c903a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 6 2 11
,D/AutoSetting( 1383): service - handleMessage() stop self
,D/AutoSetting( 1383): service - onDestroy() END
,D/AutoSetting( 1383): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=3963
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3963:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3963
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43e22768 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(4246ea60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  907): sending alarm PendingIntent{422ffba8: PendingIntentRecord{42300258 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141858, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{42381af8: PendingIntentRecord{424c53f8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143357, Int=0
D/PMS     (  907): acquireWL(423d1b40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
V/AlarmManager(  907): sending alarm PendingIntent{41db23a0: PendingIntentRecord{42475f60 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=162110, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1397/10028)
,D/PMS     (  907): acquireWL(4231de80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): acquireWL(4203e0b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1397 10028 null
,D/PMS     (  907): releaseWL(4246ea60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =382b +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE
D/PMS     (  907): releaseWL(4203e0b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(41cfa330): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=9 [122][11][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  358): [NET]res_nsend:resplen=243
D/libc    (  358): [NET]res_queryN: exit 3, ancount=10
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  907): acquireWL(422060d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,D/PMS     (  907): releaseWL(4231de80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(41cfa330): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43c83a30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43c83a30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4757): Last usage 0, idle 1453190814s, sync interval 2592000s
I/NewsWeather( 4757): setPeriodicSync in seconds 2592000
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,I/NewsWeather( 4757): Skip sync for lookup editions
,I/NewsWeather( 4757): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4757): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1397): GoogleAccountDataService.getToken()
,W/GLSActivity( 1397): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1397): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1397): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4757): Unrecoverable authentication exception
E/NewsWeather( 4757): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4757): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4757): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4757): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e7e0c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 11 3 12
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): acquireWL(423d43c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1397 10028 null
,E/NewsWeather( 4757): Failed to syncNewsAppData
,E/NewsWeather( 4757): Down sync of news app Failed, error code: SYNC_IO_ERROR,
D/PMS     (  907): releaseWL(423d43c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(425cb2f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 110757, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(422060d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1454/10028)
,D/PMS     (  907): releaseWL(425cb2f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(425780d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(425780d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,D/PMS     (  907): releaseWL(423d1b40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  907): acquireWL(4232f2d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41acb890: PendingIntentRecord{42359d68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=167787, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4232f2d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425b9fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(425b9fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1500): service - handleMessage() stop self
,D/AutoSetting( 1500): service - onDestroy() END
,D/AutoSetting( 1500): service - handleMessage() quit looper
D/Process (  907): killProcessQuiet, pid=4456
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4456:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4456
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(43e0aaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db23a0: PendingIntentRecord{42475f60 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=192205, Int=0
,D/PMS     (  907): acquireWL(4425f1d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(43e0aaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425dfce8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4425f1d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(425dfce8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(430b09e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(430b09e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(42323828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db23a0: PendingIntentRecord{42475f60 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=226702, Int=0
,D/PMS     (  907): acquireWL(42f3f020): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42323828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43abcbf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=8 [48][4][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(439bc720): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42f3f020): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  907): releaseWL(43abcbf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42604c28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,I/NewsWeather( 4757): Last usage 0, idle 1453190879s, sync interval 2592000s
,I/NewsWeather( 4757): setPeriodicSync in seconds 2592000
D/PMS     (  907): releaseWL(42604c28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4757): Skip sync for lookup editions
,I/NewsWeather( 4757): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4757): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1397): GoogleAccountDataService.getToken()
,W/GLSActivity( 1397): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1397): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1397): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/NewsWeather( 4757): Unrecoverable authentication exception
E/NewsWeather( 4757): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4757): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4757): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4757): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4757): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c23e30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 12 3 12
,D/PMS     (  907): acquireWL(42fa2ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1397 10028 null
,E/NewsWeather( 4757): Failed to syncNewsAppData
,E/NewsWeather( 4757): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(42fa2ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(425495b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 162509, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(439bc720): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(425495b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1454/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(442ddd00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(442ddd00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(43a98a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41acb890: PendingIntentRecord{42359d68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=227787, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43a98a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42532e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(42532e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(439f65d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{4243e818: PendingIntentRecord{43135ba8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228870, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4847 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{42372b28: PendingIntentRecord{42372af0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453190873416, Int=10800000
,D/PMS     (  907): releaseWL(439f65d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4847/10047)
,D/Process (  907): killProcessQuiet, pid=4475
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4475:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4475
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/PMS     (  907): acquireWL(42975b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{43b56788: PendingIntentRecord{43135ba8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=233229, Int=0
,D/PMS     (  907): releaseWL(42975b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43e34b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43e34b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b51448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db23a0: PendingIntentRecord{42475f60 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=256768, Int=0
,D/PMS     (  907): acquireWL(4465b1a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(43b51448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43a1b7c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4465b1a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(43a1b7c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43b727d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41acb890: PendingIntentRecord{42359d68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=287788, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b727d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4528): --= Surplus to requirements =--
I/jxcore-log( 4528): 
I/jxcore-log( 4528): ****TEST TOOK:  ms ****
I/jxcore-log( 4528): 
,I/jxcore-log( 4528): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4528): 
,E/cutils-trace( 4869): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4869): ====startRecUseTime====
D/htc.customization.log.level( 4869):  is 
,W/CustomizationLogLevel( 4869): Level value is invalid, use default level 2
,D/CustomizationManager( 4869):  Read ACC file spent 0.070 (s)
D/CIDMapFileReader( 4869): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4869): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4869): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4869): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4869): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4869): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4869): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4869): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4869): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4869): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4869): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4869): Parsing tag category name = system
I/CustomizationCIDLoader( 4869): Parsing tag category name = application,
I/CustomizationCIDLoader( 4869): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4869): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4869): Parsing tag category name = AudioService,
I/CustomizationCIDLoader( 4869): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4869): Parsing tag category name = Settings
D/CustomizationManager( 4869):  Read CID file spent 0.119 (s)
,D/CustomizationManager( 4869):  All configurations done spent 0.119 (s)
W/HtcNativeFlag( 4869): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4869): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4869): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4869): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4869, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  907): killProcessQuiet, pid=4528
,I/ActivityManager(  907): Killing 4528:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907):   Force finishing activity ActivityRecord{41b9a380 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  907): Copying FileAsset 0x62b190a0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1205): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4528 uid 10189
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/dalvikvm-heap( 4233): Grow heap (frag case) to 15.197MB for 1821008-byte allocation
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
I/acms    ( 1878): Unregistering com.test.thalitest
,E/acms    ( 1878): Could not unregister removed application com.test.thalitest
,D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  907): WIN DEATH: Window{41fd8d18 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  907): Client connection lost with reason: 4
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GeofencerStateMachine( 1454): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(43b73b48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1454 10028 null
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
D/VoicemailCleanupService( 1294): Cleaning up data for package: com.test.thalitest
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PMS     (  907): releaseWL(43b73b48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/Launcher( 1270): Deferring update until onResume
,D/Launcher( 1270): waitUntilResume // bindAppsRemoved
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,D/PackageBroadcastService( 1223): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4884 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/ActivityManager(  907): Delaying start of: ServiceRecord{445bd980 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
,I/MultiDex( 4884): install
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/MultiDex( 4884): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/MultiDex( 4884): loading existing secondary dex files
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/MultiDex( 4884): load found 1 secondary dex files
I/MultiDex( 4884): install done
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/PeopleContactsSync( 1223): CP2 sync disabled
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4900 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1223, uid=10028, userID:0
,I/Icing   ( 1223): doRemovePackageData com.test.thalitest
,D/PMS     (  907): acquireWL(42584de8): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,I/ProviderInstaller( 4884): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  907): releaseWL(42584de8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/MultiDex( 4900): install
,I/MultiDex( 4900): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4900): loading existing secondary dex files
,I/MultiDex( 4900): load found 1 secondary dex files
,I/MultiDex( 4900): install done
I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/ProviderInstaller( 4900): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=4490
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4490:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4490
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1383): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1383): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
,D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 2923): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4920 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  907): acquireWL(43b2da48): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,I/IcingCorporaProvider( 2923): UpdateCorporaTask done [took 179 ms] updated apps [took 179 ms] 
,W/PackageManager(  907): Unable to load service info ResolveInfo{425733b0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,E/SQLiteLog( 4884): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4884): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca06858
,E/DocListDatabase( 4884): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4884): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4884): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4884): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4884): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4884): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4884): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4884): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4884): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4884): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4884): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4884): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4884): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4884): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4884): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4884): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4884): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4884): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4884): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4884): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4884): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4884): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4884): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4884): threadid=1: thread exiting with uncaught exception (group=0x416a1e30)
E/AndroidRuntime( 4884): FATAL EXCEPTION: main
E/AndroidRuntime( 4884): Process: com.google.android.gms.drive, PID: 4884
E/AndroidRuntime( 4884): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4884): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4884): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4884): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4884): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4884): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4884): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4884): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4884): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4884): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4884): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4884): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4884): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4884): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4884): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4884): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4884): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4884): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4884): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4884): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4884): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4884): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4884): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4884): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4884): 	... 10 more
,E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
,D/Process ( 4884): killProcess, pid=4884
,D/Process ( 4884): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/SQLiteDatabase( 4920): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4920): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4920): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4920): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4920): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4920): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4920): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4920): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4920): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4920): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4920): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4920): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4920): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4920): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4920): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4920): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4920): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4920): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4920): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4920): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4920): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4920): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4920): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4920): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4920): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4920): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4920): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4920): Couldn't open ClientFlag.db for writing (will try read-only):,
E/SQLiteOpenHelper( 4920): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4920): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4920): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4920): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4920): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4920): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4920): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4920): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4920): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4920): ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4920): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4920): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4920): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4920): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4920): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4920): 	,at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4920): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4920): 	at aGL.a(GellyInjectorStoreBase.java:136)
,E/SQLiteOpenHelper( 4920): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4920): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4920): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4920): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4920): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4920): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4920): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4920): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4920): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4920): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4920): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4920): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4920): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4920): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4920): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4920): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4920): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4920): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4920): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4920): Opened ClientFlag.db in read-only mode,
,E/SQLiteDatabase( 4920): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 4920): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4920): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4920): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206),
E/SQLiteDatabase( 4920): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4920): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4920): ,	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4920): 	at ahn.a(AbstractDatabaseInstance.java:440)
,E/SQLiteDatabase( 4920): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4920): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4920): ,	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4920): threadid=11: thread exiting with uncaught exception (group=0x416a1e30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4920): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4920): Process: com.google.android.apps.docs, PID: 4920
E/AndroidRuntime( 4920): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4920): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4920): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4920): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4920): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4920): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4920): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4920): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4920): 	at aho.run(AbstractDatabaseInstance.java:455)
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
,D/Process ( 4920): killProcess, pid=4920
,D/Process ( 4920): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 ,
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4945 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  907): Recipient 4920,
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/ActivityManager(  907): Recipient 4884
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=4572
,I/ActivityManager(  907): Killing 4572:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4920) has died.
I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4884) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4572
,W/ContextImpl( 4945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4945): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4945): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4945): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4945): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4945): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4945): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4945): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4945): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4945): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4945): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4945): threadid=10: thread exiting with uncaught exception (group=0x416a1e30)
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4958 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/ActivityManager(  907): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4945): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4945): Process: com.android.keychain, PID: 4945
E/AndroidRuntime( 4945): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4945): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4945): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4945): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4945): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4945): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4945): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4945): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4945): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4945): killProcess, pid=4945
,D/Process ( 4945): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453190962931.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  907): Recipient 4945
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.android.keychain (pid 4945) has died.
,W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10924ms
,D/AppTag  ( 4958): getInstance(Context context)
,D/AppTag  ( 4958): getInstance(Context context)
,D/AppTag  ( 4958): onCreate()
,D/PMS     (  907): acquireWL(4373dad0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4233 10160 null
,I/dalvikvm-heap( 4233): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4976 uid=10098 gids={50098, 3003, 5012}
D/PMS     (  907): releaseWL(4373dad0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/DeviceManagement( 4976): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4976 dbg=false s=true
,I/DeviceManagement( 4976): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4976): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4976): WorkflowService: Starting workflow service,
I/DeviceManagement( 4976): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b07410] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4976): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4976): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4976): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4976): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4990 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4976): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4976): SessionStateController: Checking invariants...
,D/Documents( 4990): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4990): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4990): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4990): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4990): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4990): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4990): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4990): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4990): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4990): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4990): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4990): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4990): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4990): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4990): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4990): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4990): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4990): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4990): threadid=1: thread exiting with uncaught exception (group=0x416a1e30)
E/AndroidRuntime( 4990): FATAL EXCEPTION: main
E/AndroidRuntime( 4990): Process: com.android.documentsui, PID: 4990
E/AndroidRuntime( 4990): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4990): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4990): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4990): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4990): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4990): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4990): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4990): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4990): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4990): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4990): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4990): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4990): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4990): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4990): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4990): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4990): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4990): 	... 10 more
,I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5004 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  907): killProcessQuiet, pid=3928
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/ActivityManager(  907): App crashed! Process: com.android.documentsui
I/ActivityManager(  907): Killing 3928:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,D/GCM     ( 1397): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Recipient 3928
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.music (pid 3928): Died!
D/Process (  907): killProcessQuiet, pid=4626
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453190963242.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Killing 4626:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4626
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
D/Process ( 4990): killProcess, pid=4990
D/Process ( 4990): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/GCM     ( 1397): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ExternalStorage( 5004): After updating volumes, found 1 active roots
I/ActivityManager(  907): Recipient 4990
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.documentsui (pid 4990) has died.
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,E/SQLiteDatabase( 4976): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4976): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4976): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4976): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4976): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4976): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4976): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4976): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4976): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4976): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4976): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4976): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4976): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4976): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4976): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4976): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4976): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4976): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4976): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4976): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 4976): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  907): Resuming delayed broadcast
,E/SQLiteDatabase( 4976): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.,
E/SQLiteDatabase( 4976): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4976): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4976): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4976): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4976): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
,E/SQLiteDatabase( 4976): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4976): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4976): ,	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4976): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4976): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4976): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
,E/SQLiteDatabase( 4976): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4976): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4976): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/DeviceManagement( 4976): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b07410]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4976): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4976): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4976): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4976): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4976): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4976): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4976): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4976): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4976): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4976): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4976): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4976): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 4976): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5020 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 5020): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 5020): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5020): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5020): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5020): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5020): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 5020): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 5020): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 5020): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 5020): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5020): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5020): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5020): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 5020): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 5020): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5020): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5020): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5020): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5020): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 5020): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 5020): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 5020): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 5020): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 5020): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5020): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5020): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 5020): Opened MyDB.db in read-only mode
,D/Process (  907): killProcessQuiet, pid=4640
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4640:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4640
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b64c90 +
I/Prism.WidgetManager( 1270): onLoadItems() +
,I/Icing   ( 1223): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
,E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,E/Icing   ( 1223): Could not init tag ds.tag.deleted

```
