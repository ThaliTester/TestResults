#### Test 549702617e2936d_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  905): acquireWL(43cb1c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
V/AlarmManager(  905): sending alarm PendingIntent{440faa20: PendingIntentRecord{43786c30 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452525641675, Int=0
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4404 uid=10078 gids={50078}
V/AlarmManager(  905): sending alarm PendingIntent{425ff718: PendingIntentRecord{4264aed8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452525644980, Int=60000
D/PMS     (  905): releaseWL(43cb1c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
--------- beginning of /dev/log/main
D/SMSBackup( 4404): SMSBackupAgentService started
D/SMSBackup( 4404): Checking restore status
D/SMSBackup( 4404): Restore complete
D/SMSBackup( 4404): cancelCheckAlarm
D/SMSBackup( 4404): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/Finsky  ( 4013): [422] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4013): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  905): killProcessQuiet, pid=4184
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4184:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  905): Recipient 4184
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 4417): ====startRecUseTime====
D/htc.customization.log.level( 4417):  is 
W/CustomizationLogLevel( 4417): Level value is invalid, use default level 2
D/CustomizationManager( 4417):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4417): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4417): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4417): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4417): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4417): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4417): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4417): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4417): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4417): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4417): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4417): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4417): Parsing tag category name = system
I/CustomizationCIDLoader( 4417): Parsing tag category name = application
I/CustomizationCIDLoader( 4417): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4417): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4417): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4417): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4417): Parsing tag category name = Settings
D/CustomizationManager( 4417):  Read CID file spent 0.104 (s)
D/CustomizationManager( 4417):  All configurations done spent 0.104 (s)
W/HtcNativeFlag( 4417): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4417): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4417): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4417): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4417
D/PMS     (  905): acquireHCC(43787680): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(4400d9c8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1126274608
D/PMS     (  905): acquireWL(431e8878): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
E/cutils-trace( 4417): Error opening trace file: No such file or directory (2)
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c76c90
I/SocialFeedProvider( 1275): +onPause
I/SocialFeedProvider( 1275): -onPause
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4428 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1275): [trimMemory] 20
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1181): Change stage from stage3 to stage0
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
V/WebViewChromiumFactoryProvider( 4428): Binding Chromium to main looper Looper (main, tid 1) {41ab55a0}
I/LibraryLoader( 4428): Expected native library version number "",actual native library version number ""
I/chromium( 4428): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4428): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(43c24b10): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(43c98ba0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423037a0:true
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4428): 1101839888: getState(). Returning 12
D/PMS     (  905): releaseWL(43c98ba0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4428): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4428): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4428): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4428): Local Branch: 
I/Adreno-EGL( 4428): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4428): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4428):                  aa63bbd948f41d15fc72f585e
W/chromium( 4428): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4428): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4428): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4428): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4428): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4428): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4428): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4428): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4428): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4428): CordovaWebView is running on device made by: HTC
,W/AwContents( 4428): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1275
,W/ResourceType( 4428): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4428): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41afd500, mServedView=org.apache.cordova.engine.SystemWebView{41ac3128 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  905): Enable input method client, pid=4428
W/AwContents( 4428): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +281ms
,D/PMS     (  905): releaseWL(431e8878): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4428): Set native->JS mode to OnlineEventsBridgeMode
,I/SensorManager(  905): mEventCount = 1200
,D/jxcore_app_log( 4428): JniHelper::setJavaVM(0x41590048), pthread_self() = 1556535400
,D/JX-Cordova( 4428): jxcore cordova android initializing
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 11.541MB for 63974-byte allocation
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 11.596MB for 95956-byte allocation
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 11.675MB for 143930-byte allocation
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 11.778MB for 215890-byte allocation
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 11.953MB for 323830-byte allocation
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 12.626MB for 728606-byte allocation
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 13.229MB for 1092904-byte allocation
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 14.136MB for 1639352-byte allocation
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 15.455MB for 2459024-byte allocation
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(43787680): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(4400d9c8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,V/LightsService(  905): setLight #0: color=#24
,V/LightsService(  905): setLight #0: color=#20
,V/LightsService(  905): setLight #0: color=#1a
,V/LightsService(  905): setLight #0: color=#14
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{431e7d28 u0 com.htc.htclocationservice/.AutoSettingService}
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 17.579MB for 3688532-byte allocation
,W/jxcore-log( 4428): Initializing JXcore engine
,W/jxcore-log( 4428): JXcore engine is ready
,W/jxcore-log( 4428): Starting JXcore engine
,W/jxcore-log( 4428): Platform android
W/jxcore-log( 4428): 
,W/jxcore-log( 4428): Process ARCH arm
W/jxcore-log( 4428): 
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/PMS     (  905): releaseWL(43c24b10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4428): JXcore Cordova bridge is ready!
I/jxcore-log( 4428): 
,W/jxcore-log( 4428): JXcore engine is started
,I/chromium( 4428): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4428): Toggling radios to true
I/jxcore-log( 4428): 
,D/BluetoothAdapter( 4428): enable(): BT is already enabled..!
,D/WifiManager( 4428): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
,W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1302
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
,D/WifiManager( 4428): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
,D/WifiManager( 4428): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): TDLS: Tear down peers
,I/wpa_supplicant( 1181): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4428, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4428): Radios toggled
I/jxcore-log( 4428): 
I/jxcore-log( 4428): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4428): 
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1181): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1181): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1181): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1181): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7c6cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1181):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1181): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  905): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1181): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1181): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 0
I/wpa_supplicant( 1181): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(426206f0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905):    returned true
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  905): [RunningState] Stop DHCP
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): Fast associate: Old scan results
I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19738 mDataStallAlarmIntent=PendingIntent{42077920: PendingIntentRecord{424106b8 android broadcastIntent}}
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 0
I/wpa_supplicant( 1181): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
D/WifiP2pService(  905): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
D/WISPrService( 3772): >>>>>WISPrService start isConnected = false<<<<<
D/UsbnetStateTracker(  905): isAvailable+-
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
,D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  905): New client listening to asynchronous messages
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0,
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3772): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 3772): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3772): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
,D/ConnectivityService(  905): resetConnections(wlan0, 3)
,V/NativeCrypto( 1361): Read error: ssl=0x65fae7f0: I/O error during system call, Connection timed out
D/libc    (  364): [NET] entry_id:6   entry:0xb8610f60  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb8615320  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb8614fd8  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb8615428  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb8615240  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb86150e8  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb8611110  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x65fae7f0: I/O error during system call, Broken pipe
D/PMS     (  905): acquireWL(43859ea0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
D/PMS     (  905): acquireWL(435a71d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1361/10029)
D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1181): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  905): releaseWL(43859ea0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  905): releaseWL(435a71d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(435d8248): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(435d8248): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1593/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4216/10100)
D/CaptivePortalTracker(  905): NoActiveNetworkState
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/NetworkMonitor( 4291): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4291/10154)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4216/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2678/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4483 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4483): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4483): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4483): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4483): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4483): Preparing secondary program dexes.
V/DexLibLoader( 4483): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4483): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4483): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4483): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4483): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4483): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4483): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4483): Dex already copied
D/OdexVerifier( 4483): Odex verification is skipped.
,V/DexLibLoader( 4483): Creating class loader
,V/DexLibLoader( 4483): Finished creating class loader
V/DexLibLoader( 4483): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4483): Dex already copied
D/OdexVerifier( 4483): Odex verification is skipped.
,V/DexLibLoader( 4483): Creating class loader,
V/DexLibLoader( 4483): Finished creating class loader
V/DexLibLoader( 4483): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4483): Dex already copied
D/OdexVerifier( 4483): Odex verification is skipped.
V/DexLibLoader( 4483): Creating class loader
V/DexLibLoader( 4483): Finished creating class loader
V/DexLibLoader( 4483): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4483): Dex already copied
D/OdexVerifier( 4483): Odex verification is skipped.
V/DexLibLoader( 4483): Creating class loader
V/DexLibLoader( 4483): Finished creating class loader
V/DexLibLoader( 4483): Verifying classes from secondary dexes.
D/DexLibLoader( 4483): DexLibLoader.ensureDexLoaded took 17 ms
,W/dalvikvm( 4483): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4483): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-76
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-92
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1181): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1181): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1181): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1181): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1181): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 3
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 1
I/wpa_supplicant( 1181): wpa_s->is_screen_on 1
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): selected network = 1
D/wpa_supplicant( 1181): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7c6e4e8  current_ssid=0x0
D/w,pa_supplicant( 1181): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1181): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1181): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1181): check if in concurrent case
I/wpa_supplicant( 1181): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1181): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1181): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1181): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1181): RSN: PMKSA cache search - network_ctx=0xb7c6e4e8 try_opportunistic=0
D/wpa_supplicant( 1181): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1181): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1181): State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1181): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1181): nl80211: Set mode ifindex 22 iftype 2 (STATION)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1181): nl80211: Unsubscribe mgmt frames handle 0xb7c6d718 (mode change)
D/wpa_supplicant( 1181): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7c6d718
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7c6d718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7c6d718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7c6d718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7c6d718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7c6d718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7c6d718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7c6d718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7c6d718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7c6d718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7c6d718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Connect (ifindex=22),
D/wpa_supplicant( 1181):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1181):   * freq=2412
D/wpa_supplicant( 1181):   * Auth Type 0
D/wpa_supplicant( 1181):   * WPA Versions 0x2
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1181): nl80211: Connect request send successfully
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portControl=Auto,
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1181): reply (779) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000101101130
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-54
I/wpa_supplicant( 1181): tsf=0000000101101148
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-76
I/wpa_supplicant( 1181): tsf=0000000101101152
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-92
I/wpa_supplicant( 1181): tsf=0000000101101156
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=4
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-92
I/wpa_supplicant( 1181): tsf=0000000101101159
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=5
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-54
I/wpa_supplicant( 1181): tsf=0000000101101143
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ####
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 101101130, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 101101148, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2452, timestamp: 101101152, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2437, timestamp: 101101156, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 101101159, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 101101143, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/dalvikvm( 4483): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1181): nl80211: Connect event
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1181): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1181): Add randomness: count=14 entropy=6
I/wpa_supplicant( 1181): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1181): TDLS: Remove peers on association
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1181): EAPOL: enable timer tick
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1181): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1181): Get randomness: len=32 entropy=7
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
,D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,E/FbInjectorInitializer( 4483): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,I/wpa_supplicant( 1181): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7c6d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1181):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1181): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f04b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1181):    broadcast key
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1181): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1181): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1181): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1181): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1181): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): set send_ind_to_ndc = 0
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1181): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1181): EAPOL authentication completed successfully
I/wpa_supplicant( 1181): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 3772): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WISPrService( 3772): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=100 [2][2][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(44040a08): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
,D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 1
I/wpa_supplicant( 1181): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42439a60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42439a60 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4483): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4483): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4483): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=1319
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 1319:com.htc.sense.hsp/u0a55 (adj 15): empty #17
,W/fb4a(:<default>):UserScope( 4483): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4483): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4483): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 1319
,I/BroadcastQueue(  905): Schedule to resend BroadcastRecord{43c86978 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=905 callingUid=1000} for ResolveInfo{43fcf008 com.htc.sense.hsp/.weather.location.AutoSettingReceiver m=0x108000} of com.htc.sense.hsp
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4483): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  905): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4513 uid=10055 gids={50055, 1023, 3003, 5012}
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,E/dalvikvm( 4483): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4483): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4483): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4483): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4483): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4483): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4483): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4483): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4483): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4483): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4483): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4483): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4483): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4483): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4483): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4483): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4483): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4483): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1181): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 9.903MB for 39954-byte allocation
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/PluginProvider( 4513): PluginProvider onCreate
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  905): releaseWL(44040a08): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/PluginProvider( 4513): current plugin count: 18
,D/HtcAppUPService( 4513): HtcUPDataProvider onCreate()
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  905): gateway: /192.168.1.1
D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
I/dalvikvm-heap( 4483): Grow heap (frag case) to 9.980MB for 79892-byte allocation
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19740 delay=15s
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  905): WAN detection
,D/WISPrService( 3772): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
,D/MDST    (  905): default: setEnableApn apnType =default , enable=false
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@4243fbc0
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
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
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/AutoSetting( 4513): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4549 uid=10079 gids={50079, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=4216
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:2
I/ActivityManager(  905): Killing 4216:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4513/10055)
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/PMS     (  905): acquireWL(426a6be8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [1][0][0]
D/AutoSetting( 4513): service - onCreate()
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  905): releaseWL(426a6be8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/dalvikvm-heap( 4483): Grow heap (frag case) to 10.064MB for 84664-byte allocation
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1181): Change stage from stage0 to stage3
I/wpa_supplicant( 1181): wlan0: Background scan every 600 seconds
,D/AutoSetting( 4513): service - AddressCache: using context: com.htc.Weather
I/ActivityManager(  905): Recipient 4216
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/LocationManagerService(  905): request 42485c18 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/AutoSetting( 4513): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 4513): Util - check NLP state, Allowned:false, Enabled:false
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/AutoSetting( 4513): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 4513): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 4513): service - handleMessage() setting current location null
D/AutoSetting( 4513): Util - check NLP state, Allowned:false, Enabled:false
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4513/10055)
D/AutoSetting( 4513): service - onStartCommand() check timezone in 30000
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/MobileConnectivityChangeReceiver( 4549): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4549): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4549): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4549): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4575 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4549/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4549/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4549/10079)
,D/PMS     (  905): acquireWL(433316a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(423dea18): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2178): Checkin interval check for package: unspecified last checkin: 1452525607202 min interval config: 0 actual interval: 45518
D/PMS     (  905): releaseWL(433316a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2178): Checking schedule, now: 1452525652727 next: 1452525637176
,I/CheckinService( 2178): active receiver: enabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2178, uid=10029, userID:0
,I/CheckinService( 2178): Preparing to send checkin request
,I/EventLogService( 2178): Accumulating logs since 1452525603436
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 10.265MB for 75760-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{41ee5690 u0 ReceiverList{41f77280 4483 com.facebook.katana/10027/u0 remote:4239eaa8}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{41ee5690 u0 ReceiverList{41f77280 4483 com.facebook.katana/10027/u0 remote:4239eaa8}}
I/CheckinRequestBuilder( 2178): Checkin reason type: 8 attempt count: 1
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42649cf0 u0 ReceiverList{4264a290 4483 com.facebook.katana/10027/u0 remote:43032450}}
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4590 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 2178): Failed to find provider info for com.google.android.wearable.settings
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/wpa_supplicant( 1181): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1181): EAPOL: disable timer tick
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/PMS     (  905): acquireWL(42544e28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 4590): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  905): releaseWL(42544e28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2178/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4483): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4483): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4612 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4590/10151)
,V/WebViewChromiumFactoryProvider( 4590): Binding Chromium to main looper Looper (main, tid 1) {41abb278}
,I/LibraryLoader( 4590): Expected native library version number "",actual native library version number ""
,I/chromium( 4590): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4590): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(42641628): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  905): acquireWL(4377ba08): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4590): BLUETOOTH permission is missing!
D/PMS     (  905): releaseWL(42641628): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4590): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4590): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4590): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4590): Local Branch: 
I/Adreno-EGL( 4590): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4590): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4590):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 4612): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4612): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4612): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4612): install
,I/MultiDex( 4612): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4612): loading existing secondary dex files
,I/MultiDex( 4612): load found 3 secondary dex files
,I/MultiDex( 4612): install done
,I/NSApplication( 4590): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4590/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4590/10151)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4612): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4612): VFY: unable to resolve instance field 36
,W/dalvikvm( 4612): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/Process (  905): killProcessQuiet, pid=4232
,V/JNIHelp ( 4612): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3545/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3545/10160)
I/ActivityManager(  905): Killing 4232:com.htc.backup/1000 (adj 15): empty #17
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Recipient 4232
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,I/ProviderInstaller( 4612): Installed default security provider GmsCore_OpenSSL
,D/LocationInitializer( 2178): Restart initialization of location
,W/dalvikvm( 4612): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4612): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1361): Proximity feature is not enabled.
,W/dalvikvm( 4612): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4612): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4612): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4612): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4612): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/MDM     ( 1224): [123] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
D/PMS     (  905): acquireWL(425a8940): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(425a8940): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4612): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=406874626
,I/WVCdm   (  371): CdmEngine::CloseSession
,W/Settings( 4612): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/PMS     (  905): releaseWL(426206f0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4549/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 4291): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1593/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4291/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3887/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1593/10029)
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1346): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/PMS     (  905): acquireWL(43c9ee48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4612/10029)
D/PMS     (  905): acquireWL(43787e28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
D/PMS     (  905): releaseWL(43787e28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): releaseWL(43c9ee48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2678/10021)
,W/AccTypeManager( 1346): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1346): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,E/ExternalAccountType( 1346): Unsupported attribute readOnly
,D/AutoSetting( 4513): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4549): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4549): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4513/10055)
,D/AutoSetting( 4513): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 4513): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 4513): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 4513): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 4513): service - handleMessage() setting current location null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4590/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4513/10055)
D/AutoSetting( 4513): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4513): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3545/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3545/10160)
D/PMS     (  905): acquireWL(432c0a50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2178): Checkin interval check for package: unspecified last checkin: 1452525607202 min interval config: 0 actual interval: 46523
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(432c0a50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4612): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4612): OpenGL ES Shader Compiler Version: E031.24.02.07
,I/Adreno-EGL( 4612): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4612): Local Branch: 
I/Adreno-EGL( 4612): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4612): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4612):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4612): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4612): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4612): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4612): Local Branch: 
I/Adreno-EGL( 4612): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4612): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4612):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4612): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4612): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4612): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4612): Local Branch: 
I/Adreno-EGL( 4612): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4612): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4612):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  371): CdmEngine::OpenSession
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1554778997
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2178): Classify the device as Phone.
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2178): [NET] getaddrinfo-,err=8
D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2178): [NET] getaddrinfo-, 1
,D/libc    ( 2178): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =24dc +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 238
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2178): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2178): [NET] getaddrinfo-,err=8
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2178): [NET] getaddrinfo-,err=8
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2178): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2178): Sending checkin request (12402 bytes)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=11 [17][2][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-55 , oldRssi= -200
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/CheckinRequestBuilder( 2178): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2178): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,W/fb4a(:<default>):UserScope( 4483): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4483): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2178/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420eb6e0
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420eb6e0, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ce6d60
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@426a2c70
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  905): Going to sleep due to screen timeout...
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,I/CheckinRequestBuilder( 2178): Classify the device as Phone.
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  905): mWirelessDisplayManager is null
,I/CheckinTask( 2178): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2178): Checking schedule, now: 1452525655171 next: 1453048592158
,I/CheckinService( 2178): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,I/CheckinService( 2178): Checking schedule, now: 1452525655211 next: 1453048592158
,I/CheckinService( 2178): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
,D/CheckinService( 2178): Recording last checkin time for package unspecified as 1452525655216
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
D/PMS     (  905): releaseWL(423dea18): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/PMS     (  905): acquireWL(438b2318): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
,D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =885f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,I/SensorManager(  905): mEventCount = 1350
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 255
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 316ms
,E/fb4a(:<default>):LocalFbBroadcastManager( 4483): Called registerBroadcastReceiver twice.
D/NfcService( 1256): ScreenObserver: OFF
D/NfcService( 1256): applyRouting - 0
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4428
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
,D/PMS     (  905): acquireWL(43757710): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@44057e40)
,D/NfcService( 1256): applyRouting -2
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/PMN     (  905): wakingUp
D/PMS     (  905): releaseWL(43757710): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): acquireWL(43c8f9b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  905): acquireWL(439bbc60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMN     (  905): onScreenOn
D/PMS     (  905): releaseWL(439bbc60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2678): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/MtpService( 2678): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
,D/AutoSetting( 4513): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  905): acquireWL(4406c1c0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  905): releaseWL(4406c1c0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/TetherSettings( 3772): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3772): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3772): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3772): Cust_ConnectToPC   : spcsc>false
D/        ( 3772): Cust_ConnectToPC   : IPT>true
D/        ( 3772): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3772): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3772): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3772): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3772): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 4513): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19741 delay=15s
,I/PSReceiver( 3772): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3772): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/Settings( 3772): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): SET_SCREEN_ON:On
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1181): BG scan when screen On
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): Match BG scan, scan!
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =2
,I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  905):    returned true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
W/ContextImpl( 3772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
D/PMS     (  905): releaseWL(438b2318): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/SmartNS_PSService( 3772):  defaultType:0
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1116): stop update clock
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): releaseWL(43c8f9b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(426e4f40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/NetworkPolicy(  905): updateScreenOn: false
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3183 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4680 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/PMS     (  905): releaseWL(426e4f40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,W/ContextImpl( 4680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/PMS     (  905): acquireWL(440ea818): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(440ea818): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/SmartSyncUtils( 4680): isEpsOn(), nState = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/PMS     (  905): acquireWL(437474e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42657590): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4680 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1789): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1789): onScreenOn: 1452525655821
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1789): onScreenOn: 1452525655821
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/PMS     (  905): releaseWL(437474e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ce6d60
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ce6d60, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@426a2c70
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/PMS     (  905): releaseWL(42657590): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/PMN     (  905): goingToSleep
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/PMS     (  905): acquireWL(437ccd70): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/SmartSyncUtils( 4680): getMobilePolicyEnabled, result = true
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/Process (  905): killProcessQuiet, pid=4203
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
I/ActivityManager(  905): Killing 4203:com.htc.cs.dm/u0a98 (adj 15): empty #17
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19741 mDataStallAlarmIntent=PendingIntent{4252d638: PendingIntentRecord{424fe5b8 android broadcastIntent}}
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
D/PMS     (  905): acquireWL(437b8940): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
I/ActivityManager(  905): Recipient 4203
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4680): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4680): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4680): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,D/PMS     (  905): releaseWL(4377ba08): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): SET_SCREEN_ON:Off
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1181): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{43761c98 u0 com.test.thalitest/.MainActivity t2}
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  905):    returned true
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426a2c70
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426a2c70, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426a2c70, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426a2c70
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1",
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42317428 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42317428 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
D/NetworkPolicy(  905): updateScreenOn: false
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  905): acquireWL(44109668): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  905): releaseWL(44109668): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1579): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  905): acquireWL(42866898): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1789): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1789): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1789): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1789): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1789): onScreenOff
D/PMS     (  905): releaseWL(42866898): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 4513): service - mHandler: cancel location update
,D/AutoSetting( 4513): service -           changes count: 0
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(437b8940): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1181): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=15 entropy=0
D/wpa_supplicant( 1181): Add randomness: count=16 entropy=1
D/wpa_supplicant( 1181): Add randomness: count=17 entropy=2
D/wpa_supplicant( 1181): Add randomness: count=18 entropy=3
D/wpa_supplicant( 1181): Add randomness: count=19 entropy=4
D/wpa_supplicant( 1181): Add randomness: count=20 entropy=5
D/wpa_supplicant( 1181): Add randomness: count=21 entropy=6
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1181): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa,_supplicant( 1181): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1181): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=22 entropy=7
D/wpa_supplicant( 1181): Add randomness: count=23 entropy=8
D/wpa_supplicant( 1181): Add randomness: count=24 entropy=9
D/wpa_supplicant( 1181): Add randomness: count=25 entropy=10
D/wpa_supplicant( 1181): Add randomness: count=26 entropy=11
D/wpa_supplicant( 1181): Add randomness: count=27 entropy=12
D/wpa_supplicant( 1181): Add randomness: count=28 entropy=13
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP 64:7c:34:12:7f:81 type 0 added
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
,I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: DISCONNECTED -> INACTIVE
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@42644d58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@42644d58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42644d58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1181): reply (926) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000107080978
,I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000107081009
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000107081018
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
,I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000107081037
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=4
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-90
I/wpa_supplicant( 1181): tsf=0000000107081027
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=5
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-54
I/wpa_supplicant( 1181): tsf=0000000107080998
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=6
I/wpa_supplicant( 1181): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000107081047
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC4688432
I/wpa_supplicant( 1181): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 107080978, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 107081009, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 107081018, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 107081037, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 107081027, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 107080998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 107081047, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 7 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  69, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/GAV2    ( 4590): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=4312
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  905): killProcessQuiet, pid=4255
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4312:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/ActivityManager(  905): Killing 4255:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
,I/ActivityManager(  905): Recipient 4255
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4312
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/jxcore-log( 4428): Test app app.js loaded
I/jxcore-log( 4428): 
,I/Choreographer( 4428): Skipped 536 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4428): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4428): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41ac3128 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4428): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  905): releaseWL(437ccd70): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  905): acquireWL(4358e270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41adcf20: PendingIntentRecord{41fed0f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=109396, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4358e270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 10.943MB for 10276-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 10.963MB for 23110-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 10.981MB for 34660-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.009MB for 51986-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.050MB for 77974-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1346): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.117MB for 83506-byte allocation
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4706 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1275): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.117MB for 55790-byte allocation
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
W/AccTypeManager( 1346): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1346): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/Launcher( 1275): Deferring update until onResume
,D/Launcher( 1275): waitUntilResume // bindAppsUpdated
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1346): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4706): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4706): MmsConfig.loadMmsSettings
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.158MB for 72360-byte allocation
,W/dalvikvm( 4706): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4706): VFY: unable to resolve instance field 36
,W/dalvikvm( 4706): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/PackageManager(  905): Unable to load service info ResolveInfo{43b97280 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,V/JNIHelp ( 4706): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4729 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
D/libc    ( 4483): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4483): [NET] getaddrinfo-,err=8
D/libc    ( 4483): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4483): [NET] getaddrinfo-, 1
D/libc    ( 4483): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5333 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4706, uid=10111, userID:0
,W/Settings( 4706): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4706, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4706, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4706, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4706, uid=10111, userID:0
,D/MessageFrequencyProvider( 4729): onCreate
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 28
D/libc    (  364): [NET]res_nsend:resplen=93
D/libc    (  364): [NET]res_queryN: exit 3, ancount=3
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4483): [NET] getaddrinfo_proxy-, success
I/global  ( 4483): call createSocket() return a new socket.
D/libc    ( 4483): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4483): [NET] getaddrinfo-, SUCCESS
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4706, uid=10111, userID:0
,D/PMS     (  905): acquireWL(43cdb3e8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4706 10111 null
V/GetPrviateResource( 4729): GetPrviateResource
V/GetPrviateResource( 4729): GetPrviateResource
,D/MmsCustomizationProvider( 4729): query uri: content://htc-mms-customization/mms-ua/ua_string
I/[PluginManager]RegisterService( 4513): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4513): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/MmsCustomizationProvider( 4729): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/IcingCorporaProvider( 2779): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/Babel   ( 4706): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4706): MmsConfig.loadFromDatabase
D/PMS     (  905): acquireWL(425ea0a8): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(425ea0a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4394e438): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,E/Babel   ( 4706): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4706): MmsConfig.loadFromResources
,E/Babel   ( 4706): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4706): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/MessageCustFlag( 4729): sense_version=6.0
,I/ProviderInstaller( 4706): Installed default security provider GmsCore_OpenSSL
,D/BTAccessoryUtil( 4729): createReceiver
D/PMS     (  905): releaseWL(43cdb3e8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/BTAccessoryUtil( 4729): registerReceiver return intent = null
D/MessageCustFlag( 4729): sku_id=99
,W/SystemReader( 4729): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4729): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4729): networkCode: 
,D/MessageCustFlag( 4729): sku_id=99
D/MmsConfig( 4729): SIE smsPri: null
,D/MmsConfig( 4729): networkCode: 
D/HtcTelephonyCapability( 4729): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4729): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4729): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4729): Cannot find qct_8960_interface, use default value instead
,D/libc    ( 4483): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4483): [NET] getaddrinfo-,err=8
,D/PMS     (  905): releaseWL(4394e438): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  905): acquireWL(425349b8): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425349b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(4320a270): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(4242d000): PARTIAL_WAKE_LOCK  AsyncService 0x1 3545 10160 null
,D/PMS     (  905): releaseWL(4242d000): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  905): releaseWL(4320a270): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  905): acquireWL(426b8180): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,D/PMS     (  905): releaseWL(426b8180): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(425d8f98): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  905): releaseWL(425d8f98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(4408e6f8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4483 10027 null
,I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(43c9aa40): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(441cf468): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(441cf468): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): releaseWL(43c9aa40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(440feeb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(440feeb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4381ebc8): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4264e988): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4264e988): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43787540): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2178): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2178): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  905): releaseWL(4381ebc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43787540): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4320ddf8): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2178): updateResources: need to parse f{com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,I/IcingCorporaProvider( 2779): UpdateCorporaTask done [took 358 ms] updated apps [took 358 ms] 
I/ActivityManager(  905): Resuming delayed broadcast
,D/AutoSetting( 1499): service - handleMessage() stop self
,D/AutoSetting( 1499): service - onDestroy() END
,D/AutoSetting( 1499): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=3810
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3810:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  905): Recipient 3810
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b4bb30 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,I/Icing   ( 2178): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2178): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(4320ddf8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1275): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1275): onLoadItems() -
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b4bb30 -
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1241): -- N1 =0
,D/PhoneApp( 1241): -- N2 =0
,D/PhoneApp( 1241): -- N3 =0
,D/Messaging( 4729): mNeedToUpdateDate2 start
,D/MmsConfig( 4729): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4729): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4729): 
D/MmsAsyncWorkHandler( 4729): HM tk = 20001
,D/ReportIndicatorCache( 4729): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4729): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ac85d8
,I/Messaging( 4729): mccmnc> 
D/DraftCache( 4729): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4729): [DraftCache/1] refresh
,D/MmsConfig( 4729): networkCode: 
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63,
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4729): ViewCache CreatePreloadOnlyConversationList
,D/PhoneStorageUtil( 4729): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4729): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4729): createReceiver
,D/MessageCustFlag( 4729): sense_version=6.0
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1241): sku_id=99
,D/Jerry   ( 4729): start to preload cursor >>>>>>>
D/TelephUtils( 1241): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
V/MmsProvider( 1241): Update uri=content://mms, match=0
,V/MmsProvider( 1241): selection=st=129 AND m_type!=134
,D/Messaging( 4729): Reset downloading state: 0
V/MmsSystemEventReceiver( 4729): TransactionService is going to be woken up.
,D/DraftCache( 4729): [DraftCache/472] rebuildCache
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,V/TransactionService( 4729): 1-Creating TransactionService
,D/Messaging( 4729): mNeedToUpdateDate2: false
V/TransactionService( 4729): onStartCommand: 1
,D/MmsSystemEventReceiver( 4729): unRegisterForConnectionStateChanges
V/TransactionService( 4729): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4729): Loading previous transactions.
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): device_type: 1
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
D/MmsSmsV2Provider( 1241):  phoneType = -1
D/TransactionService( 4729): Force set service start id to 1
V/TransactionService( 4729): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4729): unRegisterForConnectionStateChanges
D/TransactionService( 4729): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4729): Destroying TransactionService
V/TransactionService( 4729): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Jerry   ( 1241): URI_DRAFT
,D/DraftCache( 4729): hasDraft() = false mNeedNotifyChange = true
D/Messaging( 4729): ViewCache CreatePreload
D/Messaging( 4729): ViewCache CreatePreloadOnlyMultipleOpsList
D/DraftCache( 4729): [DraftCache/472] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4729): 
D/MmsAsyncWorkHandler( 4729): HM tk = 20002
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/Cust_MMSMS( 4729): _has_set_default_values_2=true
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4729): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MsgPreferenceUtils( 4729): def_index: 0
,D/MsgPreferenceUtils( 4729): globalIndex = 1
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MsgPreferenceUtils( 4729): phone state: true
D/MsgPreferenceUtils( 4729): sd state: false
,D/MsgPreferenceUtils( 4729): vIndex = 0
,D/AccFlag ( 1241): sku_id=99
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.232MB for 82922-byte allocation
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1241): sku_id=99
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4483/10027)
,I/global  ( 4483): I/O error closing connection
I/global  ( 4483): java.net.SocketException: Socket is closed
I/global  ( 4483): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4483): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4483): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4483): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4483): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4483): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4483): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4483): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4483): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4483): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4483): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4483): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4483): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4483): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4483): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4483): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4483): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4483): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4483): Removing a connection that never existed!
D/PMS     (  905): releaseWL(4408e6f8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{441232a8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4706): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=4341
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4341:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4341
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3887
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3887:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3887
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1181): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=29 entropy=14
D/wpa_supplicant( 1181): Add randomness: count=30 entropy=15
D/wpa_supplicant( 1181): Add randomness: count=31 entropy=16
D/wpa_supplicant( 1181): Add randomness: count=32 entropy=17
D/wpa_supplicant( 1181): Add randomness: count=33 entropy=18
D/wpa_supplicant( 1181): Add randomness: count=34 entropy=19
D/wpa_supplicant( 1181): Add randomness: count=35 entropy=20
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1181): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 5,: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1181): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=36 entropy=21
D/wpa_supplicant( 1181): Add randomness: count=37 entropy=22
D/wpa_supplicant( 1181): Add randomness: count=38 entropy=23
D/wpa_supplicant( 1181): Add randomness: count=39 entropy=24
D/wpa_supplicant( 1181): Add randomness: count=40 entropy=25
D/wpa_supplicant( 1181): Add randomness: count=41 entropy=26
D/wpa_supplicant( 1181): Add randomness: count=42 entropy=27
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNative-wlan0(  905): doString: BS,S RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1181): reply (926) for get BSS: id=0,
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000124213778
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
,I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000124213813
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000124213824
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos,
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000124213845
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=4
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81,
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-90
I/wpa_supplicant( 1181): tsf=0000000124213835
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=5
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-54
I/wpa_supplicant( 1181): tsf=0000000107080998
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS]
,I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=6
I/wpa_supplicant( 1181): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000124213856
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC4688432
I/wpa_supplicant( 1181): ####
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 124213778, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 124213813, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 124213824, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 124213845, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 124213835, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 107080998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 124213856, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 7 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43114e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43114e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 4513): service - mHandler: update timezone
,D/AutoSetting( 1499): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1499): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1499): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1499): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1499): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,V/NotificationService(  905): batLight: Full, plugged
,V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
,D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
,D/AutoSetting( 1499): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/DotMatrix( 1579): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1579): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1499): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1499): service - mHandler: update timezone
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1499): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1499): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1499): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1499): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1579): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1579): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c1a928 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 8 2 11
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 4513): service - mHandler: update timezone
,D/AutoSetting( 1499): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1499): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1499): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1499): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1499): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1499): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1499): service - mHandler: update timezone
D/DotMatrix( 1579): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1579): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1499): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1499): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1499): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1499): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1579): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1579): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41eedf60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 3 7 2 11
,D/PMS     (  905): acquireWL(440a22f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{4208d3d8: PendingIntentRecord{42588b88 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124448, Int=0
,D/PMS     (  905): acquireWL(43949e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{44112f28: PendingIntentRecord{425a6f78 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135873, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=2 [93][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(440fa420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(440fa420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43949e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(440a22f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 4513): service - handleMessage() stop self
D/PMS     (  905): acquireWL(43c19160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,D/AutoSetting( 4513): service - handleMessage() quit looper
,D/AutoSetting( 4513): service - onDestroy() END
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
D/PMS     (  905): releaseWL(43c19160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43115510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/PMS     (  905): acquireWL(42838118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4398d6d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1224): Vacuum at: now=1452525686689 tag=VacuumService
,D/PMS     (  905): releaseWL(43115510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42838118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426cbd10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4398d6d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/PMS     (  905): releaseWL(426cbd10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42626508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/PMS     (  905): releaseWL(42626508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c5b548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/PMS     (  905): releaseWL(43c5b548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  905): acquireWL(44037e10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/PMS     (  905): releaseWL(44037e10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43221e48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/PMS     (  905): acquireWL(43c98e20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43c98e20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426f58c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43221e48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4321c040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/PMS     (  905): releaseWL(4321c040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype for one-off execution 8808 seconds from now (1452525687253)
,D/GetConfigurationSnapshotOperation( 1224): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1224): [NET] getaddrinfo-, 1
D/libc    ( 1224): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e49e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=100 [1][1][0]
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 242
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1224): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
,D/PMS     (  905): releaseWL(426f58c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(440b8530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/PMS     (  905): releaseWL(440b8530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44097598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/PMS     (  905): releaseWL(44097598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(4408bc38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422f2ac8: PendingIntentRecord{420f39c0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141240, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(440880f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(4408bc38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ba14 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1181): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=43 entropy=28
D/wpa_supplicant( 1181): Add randomness: count=44 entropy=29
D/wpa_supplicant( 1181): Add randomness: count=45 entropy=30
D/wpa_supplicant( 1181): Add randomness: count=46 entropy=31
D/wpa_supplicant( 1181): Add randomness: count=47 entropy=32
D/wpa_supplicant( 1181): Add randomness: count=48 entropy=33
D/wpa_supplicant( 1181): Add randomness: count=49 entropy=34
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1181): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 5,: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1181): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1181): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1181): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=50 entropy=35
D/wpa_supplicant( 1181): Add randomness: count=51 entropy=36
D/wpa_supplicant( 1181): Add randomness: count=52 entropy=37
D/wpa_supplicant( 1181): Add randomness: count=53 entropy=38
D/wpa_supplicant( 1181): Add randomness: count=54 entropy=39
D/wpa_supplicant( 1181): Add randomness: count=55 entropy=40
D/wpa_supplicant( 1181): Add randomness: count=56 entropy=41
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
,I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  905): getDiscoveryDongleList
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1181): reply (926) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000141412170
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000141412200
,I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000141412210
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81,
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000141412230
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=4
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-90
I/wpa_supplicant( 1181): tsf=0000000141412219
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=5
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-54
I/wpa_supplicant( 1181): tsf=0000000107080998
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=6
I/wpa_supplicant( 1181): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-93
I/wpa_supplicant( 1181): tsf=0000000124213856
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC4688432
I/wpa_supplicant( 1181): ####
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  69, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 141412170, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 141412200, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 141412210, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 141412230, distance: ?(cm), distanceSd: ?(cm)
,D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 141412219, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 107080998, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 124213856, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 7 to mScanResults,
,D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (7) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/Process (  905): killProcessQuiet, pid=4357
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4357:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4357
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  905): releaseWL(440880f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43622738 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=57 entropy=42
D/wpa_supplicant( 1181): Add randomness: count=58 entropy=43
D/wpa_supplicant( 1181): Add randomness: count=59 entropy=44
D/wpa_supplicant( 1181): Add randomness: count=60 entropy=45
D/wpa_supplicant( 1181): Add randomness: count=61 entropy=46
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1181): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
,I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=62 entropy=47
D/wpa_supplicant( 1181): Add randomness: count=63 entropy=48
D/wpa_supplicant( 1181): Add randomness: count=64 entropy=49
D/wpa_supplicant( 1181): Add randomness: count=65 entropy=50
D/wpa_supplicant( 1181): Add randomness: count=66 entropy=51
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1181): reply (926) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000141412170
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000158674633
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000158674643
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000141412230
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=4
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-90
I/wpa_supplicant( 1181): tsf=0000000141412219
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=5
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-54,
I/wpa_supplicant( 1181): tsf=0000000107080998
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=6
I/wpa_supplicant( 1181): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-93
I/wpa_supplicant( 1181): tsf=0000000124213856
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
,I/wpa_supplicant( 1181): ssid=UPC4688432
I/wpa_supplicant( 1181): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 141412170, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 158674633, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 158674643, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 141412230, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 141412219, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 107080998, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 124213856, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 7 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (7) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/AutoSetting( 1499): service - handleMessage() stop self
,D/AutoSetting( 1499): service - onDestroy() END
,D/AutoSetting( 1499): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4060
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 4060:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4060
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(41bdde18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41bdde18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(41aaeeb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41adcf20: PendingIntentRecord{41fed0f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=169395, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(41aaeeb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-93
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=67 entropy=52
D/wpa_supplicant( 1181): Add randomness: count=68 entropy=53
D/wpa_supplicant( 1181): Add randomness: count=69 entropy=54
D/wpa_supplicant( 1181): Add randomness: count=70 entropy=55
D/wpa_supplicant( 1181): Add randomness: count=71 entropy=56
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
,I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-93
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
,D/wpa_supplicant( 1181): Add randomness: count=72 entropy=57
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1181): Add randomness: count=73 entropy=58
D/wpa_supplicant( 1181): Add randomness: count=74 entropy=59
D/wpa_supplicant( 1181): Add randomness: count=75 entropy=60
D/wpa_supplicant( 1181): Add randomness: count=76 entropy=61
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1181): reply (779) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000175964128
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000175964155
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000158674643
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-93
I/wpa_supplicant( 1181): tsf=0000000175964189
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS],
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=5
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-54
I/wpa_supplicant( 1181): tsf=0000000107080998
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=6
I/wpa_supplicant( 1181): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-93
I/wpa_supplicant( 1181): tsf=0000000124213856
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC4688432
I/wpa_supplicant( 1181): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 175964128, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 175964155, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 158674643, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -93, frequency: 2437, timestamp: 175964189, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 107080998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 124213856, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-93], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null,
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(4259a560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(4259a560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=77 entropy=62
D/wpa_supplicant( 1181): Add randomness: count=78 entropy=63
D/wpa_supplicant( 1181): Add randomness: count=79 entropy=64
D/wpa_supplicant( 1181): Add randomness: count=80 entropy=65
D/wpa_supplicant( 1181): Add randomness: count=81 entropy=66
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: ,Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=82 entropy=67
D/wpa_supplicant( 1181): Add randomness: count=83 entropy=68
D/wpa_supplicant( 1181): Add randomness: count=84 entropy=69
D/wpa_supplicant( 1181): Add randomness: count=85 entropy=70
D/wpa_supplicant( 1181): Add randomness: count=86 entropy=71
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1181): reply (813) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000193294458,
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000193294488
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000193294499
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000193294510
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS],
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=6
I/wpa_supplicant( 1181): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-93
I/wpa_supplicant( 1181): tsf=0000000124213856
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC4688432
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=7
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-92
I/wpa_supplicant( 1181): tsf=0000000193294519
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS],
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 193294458, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 193294488, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 193294499, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 193294510, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 124213856, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 193294519, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): == (6) end of scan result ==
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=87 entropy=72
D/wpa_supplicant( 1181): Add randomness: count=88 entropy=73
D/wpa_supplicant( 1181): Add randomness: count=89 entropy=74
D/wpa_supplicant( 1181): Add randomness: count=90 entropy=75
D/wpa_supplicant( 1181): Add randomness: count=91 entropy=76
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: ,Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=92 entropy=77
D/wpa_supplicant( 1181): Add randomness: count=93 entropy=78
D/wpa_supplicant( 1181): Add randomness: count=94 entropy=79
D/wpa_supplicant( 1181): Add randomness: count=95 entropy=80
D/wpa_supplicant( 1181): Add randomness: count=96 entropy=81
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1181): reply (666) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000210563739
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000210563768
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000193294499
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000210563789
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=7
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-92
I/wpa_supplicant( 1181): tsf=0000000210563799
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 210563739, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 210563768, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 193294499, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 210563789, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 210563799, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43788f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{4237cb50: PendingIntentRecord{4311a890 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=222202, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4817 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{41b82370: PendingIntentRecord{4261a4d8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452525760852, Int=10800000
,D/PMS     (  905): releaseWL(43788f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4817/10049)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023493
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023754
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023769
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025343
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025368
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027895
,D/Process (  905): killProcessQuiet, pid=4404
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4404:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4404
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42533950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42533950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43920150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{440ffac8: PendingIntentRecord{4311a890 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=225235, Int=0
,D/PMS     (  905): releaseWL(43920150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-79
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=97 entropy=82
D/wpa_supplicant( 1181): Add randomness: count=98 entropy=83
D/wpa_supplicant( 1181): Add randomness: count=99 entropy=84
D/wpa_supplicant( 1181): Add randomness: count=100 entropy=85
D/wpa_supplicant( 1181): Add randomness: count=101 entropy=86
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211,: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-79
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=102 entropy=87
D/wpa_supplicant( 1181): Add randomness: count=103 entropy=88
D/wpa_supplicant( 1181): Add randomness: count=104 entropy=89
D/wpa_supplicant( 1181): Add randomness: count=105 entropy=90
D/wpa_supplicant( 1181): Add randomness: count=106 entropy=91
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1181): reply (666) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000227934225
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000227934255
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
,I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-79
I/wpa_supplicant( 1181): tsf=0000000227934268
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000227934280
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=7,
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-92
I/wpa_supplicant( 1181): tsf=0000000227934292
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 227934225, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 227934255, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2452, timestamp: 227934268, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 227934280, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 227934292, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 5 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList,
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(432872f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41adcf20: PendingIntentRecord{41fed0f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=229396, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(432872f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=107 entropy=92
D/wpa_supplicant( 1181): Add randomness: count=108 entropy=93
D/wpa_supplicant( 1181): Add randomness: count=109 entropy=94
D/wpa_supplicant( 1181): Add randomness: count=110 entropy=95
D/wpa_supplicant( 1181): Add randomness: count=111 entropy=96
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80,211: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=112 entropy=97
D/wpa_supplicant( 1181): Add randomness: count=113 entropy=98
D/wpa_supplicant( 1181): Add randomness: count=114 entropy=99
D/wpa_supplicant( 1181): Add randomness: count=115 entropy=100
D/wpa_supplicant( 1181): Add randomness: count=116 entropy=101
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1181): reply (666) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220,
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000245214172
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000245214199
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000245214211
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000245214221
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=7
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-92
I/wpa_supplicant( 1181): tsf=0000000245214231
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 245214172, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 245214199, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 245214211, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 245214221, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 245214231, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 5 to mScanResults
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4405c030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/PowerUI ( 1116): closing low battery warning: level=100
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(4405c030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1181): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=117 entropy=102
D/wpa_supplicant( 1181): Add randomness: count=118 entropy=103
D/wpa_supplicant( 1181): Add randomness: count=119 entropy=104
D/wpa_supplicant( 1181): Add randomness: count=120 entropy=105
D/wpa_supplicant( 1181): Add randomness: count=121 entropy=106
D/wpa_supplicant( 1181): Add randomness: count=122 entropy=107
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
,I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1181): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1181): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=123 entropy=108
D/wpa_supplicant( 1181): Add randomness: count=124 entropy=109
D/wpa_supplicant( 1181): Add randomness: count=125 entropy=110
D/wpa_supplicant( 1181): Add randomness: count=126 entropy=111
D/wpa_supplicant( 1181): Add randomness: count=127 entropy=112
D/wpa_supplicant( 1181): Add randomness: count=128 entropy=113
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1181): reply (779) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000245214172
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000262515050
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000262515060
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000262515070
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=7
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437,
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000262515080
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=8
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000262515038
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ####
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 245214172, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 262515050, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 262515060, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 262515070, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 262515080, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 262515038, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1181): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=129 entropy=114
D/wpa_supplicant( 1181): Add randomness: count=130 entropy=115
D/wpa_supplicant( 1181): Add randomness: count=131 entropy=116
D/wpa_supplicant( 1181): Add randomness: count=132 entropy=117
D/wpa_supplicant( 1181): Add randomness: count=133 entropy=118
D/wpa_supplicant( 1181): Add randomness: count=134 entropy=119
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1181): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No su,itable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1181): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=135 entropy=120
D/wpa_supplicant( 1181): Add randomness: count=136 entropy=121
D/wpa_supplicant( 1181): Add randomness: count=137 entropy=122
D/wpa_supplicant( 1181): Add randomness: count=138 entropy=123
D/wpa_supplicant( 1181): Add randomness: count=139 entropy=124
D/wpa_supplicant( 1181): Add randomness: count=140 entropy=125
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1181): reply (779) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000279843994
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000279844034
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000279844044
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
,I/wpa_supplicant( 1181): tsf=0000000279844054
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=7
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000279844068
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=8
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000279844021
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 279843994, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 279844034, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 279844044, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 279844054, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 279844068, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 279844021, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(41bdb838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(41bdb838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42624c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41adcf20: PendingIntentRecord{41fed0f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=289395, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42624c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=141 entropy=126
D/wpa_supplicant( 1181): Add randomness: count=142 entropy=127
D/wpa_supplicant( 1181): Add randomness: count=143 entropy=128
D/wpa_supplicant( 1181): Add randomness: count=144 entropy=129
D/wpa_supplicant( 1181): Add randomness: count=145 entropy=130
D/wpa_supplicant( 1181): Add randomness: count=146 entropy=131
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1181): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No su,itable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
,D/wpa_supplicant( 1181): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=147 entropy=132
D/wpa_supplicant( 1181): Add randomness: count=148 entropy=133
D/wpa_supplicant( 1181): Add randomness: count=149 entropy=134
D/wpa_supplicant( 1181): Add randomness: count=150 entropy=135
D/wpa_supplicant( 1181): Add randomness: count=151 entropy=136
D/wpa_supplicant( 1181): Add randomness: count=152 entropy=137
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1181): reply (779) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000297164560
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000297164597
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000297164607,
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000297164617
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=7
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-92
I/wpa_supplicant( 1181): tsf=0000000297164628
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=8
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000297164586
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS],
I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  905): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 297164560, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 297164597, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 297164607, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 297164617, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 297164628, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 297164586, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(44058e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44058e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
,D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=153 entropy=138
D/wpa_supplicant( 1181): Add randomness: count=154 entropy=139
D/wpa_supplicant( 1181): Add randomness: count=155 entropy=140
D/wpa_supplicant( 1181): Add randomness: count=156 entropy=141
D/wpa_supplicant( 1181): Add randomness: count=157 entropy=142
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 9
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 0
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1181): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1181): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (5 BSSes)
,D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1181): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
,I/wpa_supplicant( 1181): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1181): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=158 entropy=143
D/wpa_supplicant( 1181): Add randomness: count=159 entropy=144
D/wpa_supplicant( 1181): Add randomness: count=160 entropy=145
D/wpa_supplicant( 1181): Add randomness: count=161 entropy=146
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
,D/wpa_supplicant( 1181): Add randomness: count=162 entropy=147
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1181): reply (779) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-46
I/wpa_supplicant( 1181): tsf=0000000314503783
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000314503809
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2452
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000297164607
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-91
I/wpa_supplicant( 1181): tsf=0000000314503831
I/wpa_supplicant( 1181): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=UPC Wi-Free
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=7
I/wpa_supplicant( 1181): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1181): freq=2437
I/wpa_supplicant( 1181): level=-92
I/wpa_supplicant( 1181): tsf=0000000314503840
,I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=UPC5999698
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=8
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000297164586
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 314503783, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 314503809, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 297164607, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 314503831, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 314503840, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 297164586, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,I/jxcore-log( 4428): --= Surplus to requirements =--
I/jxcore-log( 4428): 
I/jxcore-log( 4428): ****TEST TOOK:  ms ****
I/jxcore-log( 4428): 
,I/jxcore-log( 4428): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4428): 
,E/cutils-trace( 4842): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4842): ====startRecUseTime====
D/htc.customization.log.level( 4842):  is 
,W/CustomizationLogLevel( 4842): Level value is invalid, use default level 2
,D/CustomizationManager( 4842):  Read ACC file spent 0.115 (s)
D/CIDMapFileReader( 4842): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4842): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4842): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4842): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4842): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4842): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4842): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4842): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4842): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4842): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4842): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4842): Parsing tag category name = system
,I/CustomizationCIDLoader( 4842): Parsing tag category name = application
I/CustomizationCIDLoader( 4842): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4842): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4842): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4842): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 4842): Parsing tag category name = Settings
D/CustomizationManager( 4842):  Read CID file spent 0.168 (s)
,D/CustomizationManager( 4842):  All configurations done spent 0.168 (s)
,W/HtcNativeFlag( 4842): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4842): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4842): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4842): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4842, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4428
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905): Killing 4428:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  905):   Force finishing activity ActivityRecord{43761c98 u0 com.test.thalitest/.MainActivity t2}
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1211): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4428 uid 10389
,W/PackageSettings(  905): Skipping PackageSetting{42269d40 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,W/InputDispatcher(  905): channel '440fd640 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '440fd640 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1579): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1579): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1579): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '440fd640 com.test.thalitest.MainActivity (s)'
D/PMS     (  905): acquireWL(426646a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
I/WindowState(  905): WIN DEATH: Window{440fd640 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/WindowManager(  905): WINDOW DIED Window{440fd640 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): releaseWL(426646a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/AccTypeManager( 1346): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/SQLiteConnectionPool( 2178): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1275): Deferring update until onResume
,D/Launcher( 1275): waitUntilResume // bindAppsRemoved
,D/VoicemailCleanupService( 1288): Cleaning up data for package: com.test.thalitest
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/[PluginManager]RegisterService( 4513): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 4513): handle notify Blinkfeed plugin client changed
,W/AccTypeManager( 1346): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1346): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/IcingCorporaProvider( 2779): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1346): Unsupported attribute readOnly
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4858 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  905): acquireWL(43c927a8): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43c927a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43bbed18): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2779): UpdateCorporaTask done [took 437 ms] updated apps [took 437 ms] 
,E/SQLiteDatabase( 4858): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4858): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4858): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4858): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4858): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4858): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4858): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4858): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4858): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4858): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4858): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4858): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4858): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4858): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4858): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4858): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4858): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4858): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4858): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4858): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4858): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4858): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4858): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4858): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4858): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4858): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4858): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4858): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4858): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4858): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4858): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4858): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4858): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4858): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4858): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4858): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4858): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4858): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4858): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4858): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4858): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4858): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4858): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4858): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4858): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4858): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4858): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4858): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4858): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4858): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4858): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4858): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4858): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4858): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4858): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4858): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4858): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4858): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4858): threadid=11: thread exiting with uncaught exception (group=0x41688e30)
,E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4858): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4858): Process: com.google.android.apps.docs, PID: 4858
E/AndroidRuntime( 4858): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
,E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4858): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4858): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4858): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4858): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4858): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4858): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4858): 	at aho.run(AbstractDatabaseInstance.java:455)
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
,E/SQLiteDatabase( 4858): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4858): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4858): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4858): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4858): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4858): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4858): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4858): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4858): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4858): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4858): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4858): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4858): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4858): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4858): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4858): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4858): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4858): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4858): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4858): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4858): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4858): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4858): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4858): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4858): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4858): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4858): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4858): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4858): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4858): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4858): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4876 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4858): killProcess, pid=4858
D/Process ( 4858): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/SQLiteOpenHelper( 4858): Opened ClientFlag.db in read-only mode
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4858
,I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4858) has died.
,W/ContextImpl( 4876): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4889 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4876): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4876): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4876): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4876): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4876): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4876): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4876): threadid=10: thread exiting with uncaught exception (group=0x41688e30)
E/AndroidRuntime( 4876): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4876): Process: com.android.keychain, PID: 4876
E/AndroidRuntime( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4876): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4876): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4876): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4876): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4876): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4876): killProcess, pid=4876
,D/Process ( 4876): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452525877607.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/AppTag  ( 4889): getInstance(Context context)
,I/ActivityManager(  905): Recipient 4876
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.android.keychain (pid 4876) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/AppTag  ( 4889): getInstance(Context context)
,D/AppTag  ( 4889): onCreate()
,D/PMS     (  905): acquireWL(422dd138): PARTIAL_WAKE_LOCK  AsyncService 0x1 3545 10160 null
,D/PMS     (  905): releaseWL(422dd138): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4013): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/PackageBroadcastService( 2178): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2178): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2178): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2178): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2178): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2178): Module APK com.google.android.play.games already loaded
I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2178): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2178): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66b297c0
,W/dalvikvm( 2178): threadid=47: thread exiting with uncaught exception (group=0x41688e30)
E/SQLiteLog( 2178): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2178): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca7f400
I/LocationSettingsChecker( 2178): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager(  905): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2178): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2178): Process: com.google.android.gms, PID: 2178
E/AndroidRuntime( 2178): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2178): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2178): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2178): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2178): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2178): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2178): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2178): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2178): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2178): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2178): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2178): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2178): 	at java.lang.Thread.run(Thread.java:864)
,E/DriveAsyncService( 2178): disk I/O error (code 3850)
E/DriveAsyncService( 2178): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2178): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2178): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2178): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2178): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2178): 	at java.lang.Thread.run(Thread.java:864)
,D/Process ( 2178): killProcess, pid=2178
,D/Process ( 2178): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
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
,W/PackageManager(  905): Unable to load service info ResolveInfo{425ce640 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b4bb30 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2178
I/ActivityManager(  905): Process com.google.android.gms (pid 2178) has died.
,D/PMS     (  905): handleWLDeath(43bbed18): PARTIAL_WAKE_LOCK  Icing 0x1
,D/WifiService(  905): Client connection lost with reason: 4
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10999ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20997ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20996ms
,I/ActivityManager(  905): Resuming delayed broadcast
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20993ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20992ms
E/SQLiteLog( 1361): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1361): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fdede0
,W/dalvikvm( 1361): threadid=1: thread exiting with uncaught exception (group=0x41688e30)
,E/AndroidRuntime( 1361): FATAL EXCEPTION: main
E/AndroidRuntime( 1361): Process: com.google.process.gapps, PID: 1361
E/AndroidRuntime( 1361): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1361): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1361): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1361): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1361): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1361): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1361): 	... 10 more
,E/ActivityManager(  905): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 1361): killProcess, pid=1361
,D/Process ( 1361): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4919 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4919): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4919 dbg=false s=true
,I/DeviceManagement( 4919): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4919): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4919): WorkflowService: Starting workflow service
I/DeviceManagement( 4919): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ae7f68] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4919): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4919): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4919): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4919): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4933 uid=10099 gids={50099, 3003, 5012}
,I/ActivityManager(  905): Recipient 1361
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 4919): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4919): SessionStateController: Checking invariants...
I/ActivityManager(  905): Process com.google.process.gapps (pid 1361) has died.
D/WifiService(  905): Client connection lost with reason: 4
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30844ms
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,D/Documents( 4933): Loading roots for com.android.providers.downloads.documents

```
