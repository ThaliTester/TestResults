#### Test 55311151a2306df_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1118): WifiActivity: 1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
--------- beginning of /dev/log/main
E/cutils-trace( 4395): Error opening trace file: No such file or directory (2)
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  902):    returned true
D/WifiStateMachine(  902): [ScoreAP] + current TXpacket:70, mTXpacketCount:70, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  902): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/CustomizationManager( 4395): ====startRecUseTime====
D/htc.customization.log.level( 4395):  is 
W/CustomizationLogLevel( 4395): Level value is invalid, use default level 2
D/CustomizationManager( 4395):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 4395): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4395): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4395): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4395): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4395): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4395): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4395): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4395): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4395): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4395): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4395): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4395): Parsing tag category name = system
I/CustomizationCIDLoader( 4395): Parsing tag category name = application
I/CustomizationCIDLoader( 4395): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4395): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4395): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4395): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4395): Parsing tag category name = Settings
D/CustomizationManager( 4395):  Read CID file spent 0.107 (s)
D/CustomizationManager( 4395):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4395): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4395): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4395): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4395): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  902): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  902): <<nativeAcquireCpuPerfWakeLock()
I/Intent  (  902): @test_code: getHtcIntentFlag: 0 obj: 1124016696
W/CpuWake (  902): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  902): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  902): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  902): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4395
D/PMS     (  902): acquireHCC(433ca958): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 902 1000 null
D/PMS     (  902): acquireHCC(43580cf0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 902 1000 null
I/FeedHostManager( 1286): [onPause]
I/FeedProviderManager( 1286): onPause
I/FeedHostManager( 1286): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f54810
I/SocialFeedProvider( 1286): +onPause
I/SocialFeedProvider( 1286): -onPause
D/PMS     (  902): acquireWL(43b60d98): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 902 1000 null
I/ActivityManager(  902): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4406 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1286): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4406): Binding Chromium to main looper Looper (main, tid 1) {41a81cd0}
I/LibraryLoader( 4406): Expected native library version number "",actual native library version number ""
I/chromium( 4406): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4406): Initializing chromium process, renderers=0
D/PMS     (  902): acquireWL(43551038): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  902): releaseWL(43551038): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/System.err(  902): java.lang.Throwable: stack dump
D/BluetoothManagerService(  902): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  902): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4407fcc8:true
,D/PMS     (  902): acquireWL(44098f10): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
W/System.err(  902): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  902): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  902): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  902): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  902): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4406): 1101643976: getState(). Returning 12
,I/Adreno-EGL( 4406): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4406): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4406): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4406): Local Branch: 
I/Adreno-EGL( 4406): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4406): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4406):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{41fec160 u0 com.htc.htclocationservice/.AutoSettingService}
,W/chromium( 4406): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4406): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4406): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4406): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4406): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4406): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4406): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4406): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4406): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4406): CordovaWebView is running on device made by: HTC
D/WIFI_ICON( 1118): WifiActivity: 1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/AwContents( 4406): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  902): Disable input method client, pid=1286
,I/InputMethodManagerService(  902): Enable input method client, pid=4406
W/ResourceType( 4406): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4406): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41acd778, mServedView=org.apache.cordova.engine.SystemWebView{41a933e0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4406): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  902): Displayed com.test.thalitest/.MainActivity: +397ms
,D/PMS     (  902): releaseWL(43b60d98): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4406): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4406): JniHelper::setJavaVM(0x4155c048), pthread_self() = 1662993080
,D/JX-Cordova( 4406): jxcore cordova android initializing
,I/dalvikvm-heap( 4406): Grow heap (frag case) to 11.636MB for 96598-byte allocation
,I/dalvikvm-heap( 4406): Grow heap (frag case) to 11.715MB for 144892-byte allocation
,I/dalvikvm-heap( 4406): Grow heap (frag case) to 11.834MB for 217334-byte allocation
,I/dalvikvm-heap( 4406): Grow heap (frag case) to 12.006MB for 325996-byte allocation
,I/dalvikvm-heap( 4406): Grow heap (frag case) to 12.272MB for 488990-byte allocation
,I/dalvikvm-heap( 4406): Grow heap (frag case) to 13.281MB for 1100216-byte allocation
,I/dalvikvm-heap( 4406): Grow heap (frag case) to 14.191MB for 1650320-byte allocation
,I/dalvikvm-heap( 4406): Grow heap (frag case) to 15.534MB for 2475476-byte allocation
,W/CpuWake (  902): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  902): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  902): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  902): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  902): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  902): <<release mCpuPerf_Freq wakelock
D/PMS     (  902): releaseHCC(433ca958): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  902): releaseHCC(43580cf0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4406): Grow heap (frag case) to 17.667MB for 3713210-byte allocation
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 4406): Initializing JXcore engine
,W/jxcore-log( 4406): JXcore engine is ready
,W/jxcore-log( 4406): Starting JXcore engine
,W/jxcore-log( 4406): Platform android
W/jxcore-log( 4406): 
,W/jxcore-log( 4406): Process ARCH arm
W/jxcore-log( 4406): 
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1135): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
,I/jxcore-log( 4406): JXcore Cordova bridge is ready!
I/jxcore-log( 4406): 
,W/jxcore-log( 4406): JXcore engine is started
,I/chromium( 4406): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  902): releaseWL(44098f10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  902): mEventCount = 1050
,I/ActivityManager(  902): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4452 uid=10077 gids={50077}
,D/PMS     (  902): acquireWL(4360e4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10077}
,V/AlarmManager(  902): sending alarm PendingIntent{41fdbc90: PendingIntentRecord{41b1a750 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452155900603, Int=60000
,D/PMS     (  902): releaseWL(4360e4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4452): SMSBackupAgentService started
,D/SMSBackup( 4452): Checking restore status
D/SMSBackup( 4452): Restore complete
,D/SMSBackup( 4452): cancelCheckAlarm
,D/SMSBackup( 4452): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  902): killProcessQuiet, pid=4228
,I/ActivityManager(  902): Killing 4228:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  902): Recipient 4228
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  902): Client connection lost with reason: 4
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 4406): Toggling radios to true
I/jxcore-log( 4406): 
,D/BluetoothAdapter( 4406): enable(): BT is already enabled..!
,D/WifiManager( 4406): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  902): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  902): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  902): Settings:Agentvalue: 2
W/Settings:Agent(  902): >> traceCallingStack()
W/Settings:Agent(  902): Process.myPid(): 902
W/Settings:Agent(  902): Process.myTid(): 1284
W/Settings:Agent(  902): Process.myUid(): 1000
W/Settings:Agent(  902): 
W/Settings:Agent(  902): 
W/System.err(  902): java.lang.Throwable: stack dump
W/System.err(  902): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  902): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  902): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  902): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  902): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  902): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  902): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  902): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  902): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  902): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  902): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  902): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  902): 
,W/Settings:Agent(  902): << traceCallingStack(): 1(ms)
D/WifiManager( 4406): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiManager( 4406): reconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  902): doBoolean: DISCONNECT
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): TDLS: Tear down peers
I/wpa_supplicant( 1135): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  902): setWifiEnabled: true pid=4406, uid=10348
E/WifiService(  902): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  902): isSprintWifiRestricted(): false
I/WifiService(  902): isMdmWifiRestricted(): false
D/WifiSettingsStore(  902): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  902): New client listening to asynchronous messages
I/jxcore-log( 4406): Radios toggled
I/jxcore-log( 4406): 
D/BluetoothManagerService(  902): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  902): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4406): Received device characteristics:
I/jxcore-log( 4406): Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4406): Bluetooth name: HTC Desire 820
I/jxcore-log( 4406): Device name: HTC-HTC Desire 820
I/jxcore-log( 4406): 
I/jxcore-log( 4406): Perf Test app loaded loaded
I/jxcore-log( 4406): 
I/Choreographer( 4406): Skipped 78 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4406): check test folder
I/jxcore-log( 4406): 
,I/jxcore-log( 4406): found test : ./testFindPeers.js
I/jxcore-log( 4406): 
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1135): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1135): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1135): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  902): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  902): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  902): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  902): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1135): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1135): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1135): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1135): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1135): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8586bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1135):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1135): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1135): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1135): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1135): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  902): interfaceLinkStateChanged wlan0, false
D/Tethering(  902): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1135): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1135): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1135): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1135): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1135): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1135): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1135): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1135): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1135): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1135): nl80211: Ignore disconnect event triggered during reassociation
,D/Tethering(  902): [isWifi] getHotspotEnabled: false
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  902):    returned true
D/WifiPerfLock(  902): release()
,D/WifiStateMachine(  902): PerfLock released for exiting ConnectedState
D/Tethering(  902): interfaceLinkStateChanged wlan0, false
,D/Tethering(  902): interfaceStatusChanged wlan0, false
,D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  902): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1135): Power_Mode_Type mode = 0
I/wpa_supplicant( 1135): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 61
,I/jxcore-log( 4406): found test : ./testSendData.js
I/jxcore-log( 4406): 
D/WifiNative-wlan0(  902):    returned true
,D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  902):    returned true
D/ConnectivityService(  902): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  902): acquireWL(43569100): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 902 1000 null
D/WifiP2pService(  902): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  902): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  902): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  902): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  902): [RunningState] Stop DHCP
D/WifiNative-wlan0(  902): doBoolean: RECONNECT
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): Fast associate: Old scan results
I/wpa_supplicant( 1135): wpa_supplicant_scan enter
I/wpa_supplicant( 1135): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1135): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1135): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1135): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  902): stopDataStallAlarm: current tag=20348 mDataStallAlarmIntent=PendingIntent{44024940: PendingIntentRecord{4263e568 android broadcastIntent}}
D/WifiNative-wlan0(  902):    returned true
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  902): Enter handleNetworkDisconnect
,D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  902): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
,D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): Power_Mode_Type mode = 0
I/wpa_supplicant( 1135): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  902):    returned true
D/UsbnetStateTracker(  902): isAvailable+-
D/UsbnetStateTracker(  902): reconnect
,D/UsbnetStateTracker(  902): isAvailable+-
D/ConnectivityService(  902): Provision feature enable=false
D/ConnectivityService(  902): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  902): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiP2pService(  902): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  902): default: reconnect()
D/MDST    (  902): default: setTeardownRequested(false)
D/MDST    (  902): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  902): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  902): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  902): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4190): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  902): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4190): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiService(  902): New client listening to asynchronous messages
W/ConnectivityService(  902): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  902): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  902): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,D/WifiStateMachine(  902): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4190): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  902): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4190): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] entry_id:3   entry:0xb8188320  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8187fd8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8188428  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb8188240  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb81880e8  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
W/ConnectivityService(  902): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  902): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  902): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  902): handleConnectivityChange: resetting
D/ConnectivityService(  902): resetConnections(wlan0, 3)
D/ConnectivityService(  902): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  902): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  902): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  902): acquireWL(4231e610): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
D/WirelessDisplayService(  902): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  902): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  902): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  902): acquireWL(41cf6758): PARTIAL_WAKE_LOCK  NetworkStats 0x1 902 1000 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  902): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  902): acquireWL(42546150): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
D/PMS     (  902): releaseWL(42546150): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/WifiStateMachine(  902): startScan Pid: 902 Uid 1000
,D/WifiNative-wlan0(  902): doBoolean: SCAN
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  902):    returned false
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/BatSI   (  902): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  902): reportInetCondition for net -1, percentage: 0 by  (1360/10028)
D/PMS     (  902): releaseWL(4231e610): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  902): releaseWL(41cf6758): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  902): handleInetConditionChange: no active default network - ignore
,I/chromium( 4406): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  902): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  902): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4473 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
,D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.htc.launcher (1286/10075)
D/PMS     (  902): acquireWL(42431140): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
D/GpsLocationProvider(  902): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  902): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  902): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  902): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  902): DelayedCaptiveCheckState
D/CaptivePortalTracker(  902): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  902): NoActiveNetworkState
D/Tethering(  902): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  902): bSetPropertyMultiRAB:false
,I/ConnectivityHelper( 1286): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  902): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1861/1000)
D/PMS     (  902): releaseWL(42431140): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.docs (4294/10100)
I/Tethering(  902): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  902): ipv4Default null
,I/Tethering(  902): No IPv4 upstream interface, giving up.
,D/Tethering(  902): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1434/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.docs (4294/10100)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,I/MusicStore( 4473): Database version: 95
,W/ContextImpl( 4473): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4473): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4473): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4473): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4473): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4473, uid=10154, userID:0
,D/WifiDisplayAdapter(  902): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  902):     Client/Owner: Client
D/WifiDisplayAdapter(  902):     GroupId: 
D/WifiDisplayAdapter(  902):     Passphrase: 
D/WifiDisplayAdapter(  902):     SessionId: 0
D/WifiDisplayAdapter(  902):     IP Address: }
,D/MediaRouterService(  902): Client com.google.android.music (pid 4473): Registered
,D/WifiDisplayAdapter(  902): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  902):     Client/Owner: Client
D/WifiDisplayAdapter(  902):     GroupId: 
D/WifiDisplayAdapter(  902):     Passphrase: 
D/WifiDisplayAdapter(  902):     SessionId: 0
D/WifiDisplayAdapter(  902):     IP Address: }
I/MediaRouter( 4473): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.music (4473/10154)
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (2388/10021)
,I/ActivityManager(  902): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4493 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4473): getSelectedRoute
,I/NetworkMonitor( 4473): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.google.android.music (4473/10154)
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4473, uid=10154, userID:0
,D/Process (  902): killProcessQuiet, pid=3436
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4493): ACRA is enabled for com.facebook.katana, intializing...
I/ActivityManager(  902): Killing 3436:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3436
,D/ACRA    ( 4493): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4493): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 4493): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4493): Preparing secondary program dexes.
V/DexLibLoader( 4493): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4493): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4493): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4493): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4493): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4493): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4493): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4493): Dex already copied
D/OdexVerifier( 4493): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4493): Creating class loader
,V/DexLibLoader( 4493): Finished creating class loader
V/DexLibLoader( 4493): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4493): Dex already copied
D/OdexVerifier( 4493): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4493): Creating class loader
,V/DexLibLoader( 4493): Finished creating class loader
V/DexLibLoader( 4493): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4493): Dex already copied
D/OdexVerifier( 4493): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4493): Creating class loader
,V/DexLibLoader( 4493): Finished creating class loader
V/DexLibLoader( 4493): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4493): Dex already copied
D/OdexVerifier( 4493): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4493): Creating class loader
,V/DexLibLoader( 4493): Finished creating class loader
,V/DexLibLoader( 4493): Verifying classes from secondary dexes.
,D/DexLibLoader( 4493): DexLibLoader.ensureDexLoaded took 23 ms
,W/dalvikvm( 4493): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4493): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4493): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4493): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4493): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4493): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4493): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1135): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1135): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1135): nl80211: Survey data missing
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1135): Sorted scan results
I/wpa_supplicant( 1135): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-55
I/wpa_supplicant( 1135): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1135): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1135): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1135): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1135): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
D/wpa_supplicant( 1135): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1135): Add randomness: count=14 entropy=0
D/wpa_supplicant( 1135): Add randomness: count=15 entropy=1
D/wpa_supplicant( 1135): Add randomness: count=16 entropy=2
D/wpa_supplicant( 1135): Add randomness: count=17 entropy=3
D/wpa_supplicant( 1135): Add randomness: count=18 entropy=4
D/wpa_supplicant( 1135): Add randomness: count=19 entropy=5
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1135): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1135): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1135): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1135): wpa_supplicant_pick_network+
I/wpa_supplicant( 1135): Selecting BSS from priority group 1
I/wpa_supplicant( 1135): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1135): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1135): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1135): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1135):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1135):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-52
I/wpa_supplicant( 1135): Start print parameters
I/wpa_supplicant( 1135): wpa_s->wpa_state is 3
I/wpa_supplicant( 1135): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1135): isConcurrentMode() is 0
I/wpa_supplicant( 1135): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1135): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1135): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1135): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1135): wpa_s->reassociate is 1
I/wpa_supplicant( 1135): wpa_s->is_screen_on 1
I/wpa_supplicant( 1135): wpa_s->ifname wlan0
I/wpa_supplicant( 1135): End print parameters
I/wpa_supplicant( 1135): selected network = 3
D/wpa_supplicant( 1135): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85884e8  current_ssid=0x0
D,/wpa_supplicant( 1135): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1135): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1135): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1135): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1135): check if in concurrent case
I/wpa_supplicant( 1135): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState,
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
D/wpa_supplicant( 1135): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1135): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1135): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1135): RSN: PMKSA cache search - network_ctx=0xb85884e8 try_opportunistic=0
D/wpa_supplicant( 1135): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1135): RSN: No PMKSA cache entry found,
I/wpa_supplicant( 1135): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1135): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1135): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1135): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1135): nl80211: Unsubscribe mgmt frames handle 0xb8587718 (mode change)
D/wpa_supplicant( 1135): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8587718
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718,
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1135):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1135):   * freq=2412
D/wpa_supplicant( 1135):   * Auth Type 0
D/wpa_supplicant( 1135):   * WPA Versions 0x2
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1135): nl80211: Connect request send successfully
D/wpa_supplicant( 1135): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1135): reply (779) for get BSS: id=0
I/wpa_supplicant( 1135): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1135): freq=5220
I/wpa_supplicant( 1135): level=-55
I/wpa_supplicant( 1135): tsf=0000000108151107
I/wpa_supplicant( 1135): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1135): ssid=NG7005g
I/wpa_supplicant( 1135): ====
I/wpa_supplicant( 1135): id=1
I/wpa_supplicant( 1135): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1135): freq=2437
I/wpa_supplicant( 1135): level=-84
I/wpa_supplicant( 1135): tsf=0000000108151131
I/wpa_supplicant( 1135): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1135): ssid=UPC Wi-Free
I/wpa_supplicant( 1135): ====
I/wpa_supplicant( 1135): id=2
I/wpa_supplicant( 1135): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1135): freq=2437
I/wpa_supplicant( 1135): level=-84
I/wpa_supplicant( 1135): tsf=0000000108151135
I/wpa_supplicant( 1135): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1135): ssid=UPC5999698
I/wpa_supplicant( 1135): ====
I/wpa_supplicant( 1135): id=3
I/wpa_supplicant( 1135): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1135): freq=2412
I/wpa_supplicant( 1135): level=-52
I/wpa_supplicant( 1135): tsf=0000000108151124
I/wpa_supplicant( 1135): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1135): ssid=NG700
I/wpa_supplicant( 1135): ====
I/wpa_supplicant( 1135): id=4
I/wpa_supplicant( 1135): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1135): freq=2412
I/wpa_supplicant( 1135): level=-76
I/wpa_supplicant( 1135): tsf=0000000108151128
I/wpa_supplicant( 1135): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1135): ssid=Gonzos
I/wpa_supplicant( 1135): ====
I/wpa_supplicant( 1135): id=5
I/wpa_supplicant( 1135): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1135): freq=2412
I/wpa_supplicant( 1135): level=-52
I/wpa_supplicant( 1135): tsf=0000000108151119
I/wpa_supplicant( 1135): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1135): ssid=01ABC
I/wpa_supplicant( 1135): ####
D/WirelessDisplayService(  902): getDiscoveryDongleList
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): == begin of scan result ==
D/WifiStateMachine(  902): == (6) end of scan result ==
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 5220, timestamp: 108151107, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 1: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 108151131, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 108151135, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 3: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 108151124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 108151128, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 108151119, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 6 to mScanResults
D/BatSI   (  902): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/wpa_supplicant( 1135): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1135): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1135): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1135): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1135): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1135): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1135): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1135): nl80211: Connect event
D/wpa_supplicant( 1135): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1135): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1135): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1135): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1135): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1135): Add randomness: count=20 entropy=6
I/wpa_supplicant( 1135): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1135): TDLS: Remove peers on association
D/wpa_supplicant( 1135): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1135): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1135): EAPOL: enable timer tick
D/wpa_supplicant( 1135): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1135): htc_wext_set_keepalive +
I/wpa_supplicant( 1135): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1135): getPrivFuncNum +	
I/wpa_supplicant( 1135): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1135): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1135): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  902): interfaceLinkStateChanged wlan0, false
,D/Tethering(  902): interfaceStatusChanged wlan0, false
D/Tethering(  902): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  902): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  902): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  902): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  902): interfaceLinkStateChanged wlan0, true
D/Tethering(  902): interfaceStatusChanged wlan0, true
D/WifiMonitor(  902): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  902): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  902): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
,D/Tethering(  902): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  902): Enter handleAssociatedWithEvent
D/WifiStateMachine(  902): Associated
D/WifiStateMachine(  902): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  902): Exit handleAssociatedWithEvent
I/wpa_supplicant( 1135): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1135): Get randomness: len=32 entropy=7
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  902): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
,D/WifiStateMachine(  902): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  902): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  902): This record is existed, only update it...
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
,I/wpa_supplicant( 1135): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb85879f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1135):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1135): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1135): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f35b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1135):    broadcast key
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1135): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
E/wpa_supplicant( 1135): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1135): State: GROUP_HANDSHAKE -> COMPLETED,
I/wpa_supplicant( 1135): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1135): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1135): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1135): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1135): set send_ind_to_ndc = 0
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING (1)+,
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1135): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1135): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1135): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1135): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1135): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 1135): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1135): EAPOL authentication completed successfully
I/wpa_supplicant( 1135): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 79
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1135): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 1135): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1135): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  902): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  902): interfaceLinkStateChanged wlan0, true
D/Tethering(  902): interfaceStatusChanged wlan0, true
,D/Tethering(  902): [isWifi] getHotspotEnabled: false,
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
,D/WifiStateMachine(  902): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  902): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  902): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  902): This record is existed, only update it...
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  902): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  902): Provision feature enable=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4190): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4190): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
D/ConnectivityService(  902): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,W/dalvikvm( 4493): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/DhcpStateMachine(  902): [StoppedState] Start DHCP
D/WifiStateMachine(  902): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
,D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): Power_Mode_Type mode = 1
I/wpa_supplicant( 1135): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  902):    returned null
E/WifiStateMachine(  902): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  902): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  902):    returned null
D/WifiStateMachine(  902): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  902): acquireWL(440e97e0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 902 1000 null
D/WifiStateMachine(  902): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  902): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42629548 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42629548 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
,W/dalvikvm( 4493): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4493): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4493): Verify
,D/WifiService(  902): New client listening to asynchronous messages
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4493): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4493): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  902): killProcessQuiet, pid=3174
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 3174:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  902): acquireWL(425fbe70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1240 10028 null
,I/ActivityManager(  902): Recipient 3174
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(42d807a8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1240 10028 null
,D/PMS     (  902): releaseWL(425fbe70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1360): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,D/PMS     (  902): releaseWL(42d807a8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1385): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  902): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4524 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
,D/AutoSetting( 1385): Util - no network available!
,D/AutoSetting( 1385): service - onCreate()
,D/AutoSetting( 1385): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
,D/AutoSetting( 1385): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  902): request 4248db98 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  902): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1385): service - mHandler: cancel location update
,D/AutoSetting( 1385): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4493): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4493): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4524): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4524): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4524): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4524): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4493): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  902): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4540 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4493): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  902): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4557 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  902): killProcessQuiet, pid=3855
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Killing 3855:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3855
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 9.956MB for 84664-byte allocation
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4557): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4557): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4557): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4557): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4557): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 9.971MB for 28144-byte allocation
,E/dalvikvm( 4493): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4493): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4493): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4493): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4493): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4493): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4493): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4493): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4493): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4493): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4493): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4493): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4493): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4493): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4493): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4493): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4493): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4493): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 10.042MB for 39954-byte allocation
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.magazines (4557/10151)
I/dalvikvm-heap( 4493): Grow heap (frag case) to 10.119MB for 79892-byte allocation
V/WebViewChromiumFactoryProvider( 4557): Binding Chromium to main looper Looper (main, tid 1) {41a8c188}
I/LibraryLoader( 4557): Expected native library version number "",actual native library version number ""
I/chromium( 4557): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4557): Initializing chromium process, renderers=0
,D/PMS     (  902): acquireWL(43615378): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4557): BLUETOOTH permission is missing!
D/PMS     (  902): acquireWL(43799d50): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  902): releaseWL(43799d50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4557): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4557): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4557): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4557): Local Branch: 
I/Adreno-EGL( 4557): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4557): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4557):                  aa63bbd948f41d15fc72f585e
,D/wpa_supplicant( 1135): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1135): EAPOL: disable timer tick
,I/NSApplication( 4557): Starting up...
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.magazines (4557/10151)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.magazines (4557/10151)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
,D/Process (  902): killProcessQuiet, pid=3990
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 3990:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,W/BroadcastQueue(  902): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{431311f8 u0 ReceiverList{431310d8 4493 com.facebook.katana/10026/u0 remote:42fc71c8}}
,W/BroadcastQueue(  902): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{431311f8 u0 ReceiverList{431310d8 4493 com.facebook.katana/10026/u0 remote:42fc71c8}}
,W/BroadcastQueue(  902): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43492758 u0 ReceiverList{434926f8 4493 com.facebook.katana/10026/u0 remote:43467bb8}}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/PMS     (  902): acquireWL(44021148): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
,D/PMS     (  902): releaseWL(44021148): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1434): Unknown pending intent to remove.
D/PMS     (  902): acquireWL(43542160): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
D/PMS     (  902): releaseWL(43542160): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4493): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 3990
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4493): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/libc    (  902): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  902): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1135): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  902):    returned true
,D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  902):    returned true
,D/WifiStateMachine(  902): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  902): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  902): releaseWL(440e97e0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1135): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
D/WifiStateMachine(  902): gateway: /192.168.1.1
,D/WifiNative-wlan0(  902): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1135): WiFi gateway: 0x101a8c0
,D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiNative-wlan0(  902):    returned true
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  902): VerifyingLinkState enter
D/WifiStateMachine(  902): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  902): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  902): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,V/NetworkPolicy(  902): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  902): startDataStallAlarm: tag=20350 delay=15s
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  902): WAN detection
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  902): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  902): Provision feature enable=false
D/ConnectivityService(  902): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  902): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  902): default: teardown()
D/MDST    (  902): default: setTeardownRequested(true)
D/MDST    (  902): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 4190): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  902): default: setTeardownRequested(true)
D/ConnectivityService(  902): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  902): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  902): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  902): Unexpected mtu value: android.net.wifi.WifiStateTracker@423b2e88
D/ConnectivityService(  902): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  902): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  902): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  902): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  902): handleConnectivityChange: resetting
D/Nat464Xlat(  902): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  902): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  902): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  902): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  902): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  902): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  902): acquireWL(436020a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 902 1000 null
D/WirelessDisplayService(  902): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  902):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  902): acquireWL(43fc99c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1240 10028 null
D/PMS     (  902): acquireWL(44066488): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1240 10028 null
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
I/CheckinService( 1240): Preparing to send checkin request
,I/EventLogService( 1240): Accumulating logs since 1452155852442
D/PMS     (  902): releaseWL(43fc99c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1240): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1240): Using GMS GoogleHttpClient
,D/ConnectivityService(  902): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  902): releaseWL(436020a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  902): getNetworkInfo networkType=9 called by com.google.android.gms (1240/10028)
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  902): getNetworkInfo networkType=0 called by com.google.android.gms (1240/10028)
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1240): awaiting user notification for token
D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41b4a208 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 0 7 2 12
,I/ActivityManager(  902): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4631 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4631): install
,I/MultiDex( 4631): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4631): loading existing secondary dex files
,I/MultiDex( 4631): load found 1 secondary dex files
,I/MultiDex( 4631): install done
,I/ProviderInstaller( 4631): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4631): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4631): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4631): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4631): Local Branch: 
I/Adreno-EGL( 4631): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4631): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4631):                  aa63bbd948f41d15fc72f585e
,I/PMS     (  902): Going to sleep due to screen timeout...
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420daf78
,W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  902): pid=902, uid=1000
,W/SensorService(  902): Active sensors: size = 2
I/ActivityManager(  902): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  902): Couldn't get kernel wake lock stats
V/LightsService(  902): setLight #2: color=#0
D/qdlights(  902): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  902): setLight #0: color=#0
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420daf78, eanble = 0, strlen(mName) = 59
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  902): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42279aa0
W/SensorService(  902): Listener[1] = com.htc.smartdim.sensor_eye@41d30c88
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/dalvikvm( 4406): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4406): threadid=1: thread exiting with uncaught exception (group=0x41654e30)
E/AndroidRuntime( 4406): FATAL EXCEPTION: main
E/AndroidRuntime( 4406): Process: com.test.thalitest, PID: 4406
E/AndroidRuntime( 4406): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4406): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4406): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4406): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4406): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4406): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4406): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4406): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4406): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4406): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4406): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4406): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4406): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4406): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4406): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4406): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4406): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4406): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4406): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  902): App crashed! Process: com.test.thalitest
D/WirelessDisplayService(  902): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  902): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  902): mWirelessDisplayManager is null
W/ActivityManager(  902):   Force finishing activity com.test.thalitest/.MainActivity
D/PMS     (  902): acquireWL(41f0e230): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 902 1000 null
,I/Adreno-EGL( 4631): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4631): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4631): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4631): Local Branch: 
I/Adreno-EGL( 4631): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4631): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4631):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  902): releaseWL(43569100): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  902): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiStateMachine(  902): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  902): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=50 [2][1][0]
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  902): BroadcastRSSIForIMS, newrssi =-52 , oldRssi= -200
,D/SurfaceControl(  902): Excessive delay in blankDisplay() while turning screen off: 379ms
D/PMS     (  902): nativeSetInteractive:false
D/PMS     (  902): nativeSetInteractive:false done
D/PMS     (  902): nativeSetAutoSuspend:true
D/PMS     (  902): nativeSetAutoSuspend:true done
,V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1135): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
D/NfcService( 1270): ScreenObserver: OFF
,D/NfcService( 1270): applyRouting - 0
,V/Tethering(  902): bSetPropertyMultiRAB:false
D/Tethering(  902): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  902): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  902): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  902): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  902): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  902): Found interface wlan0
,D/Tethering(  902): TetherMasterSM: InitialState processMessage what=3
D/HABCtrl (  902): TPE algorithm. remove timeout.
D/PMS     (  902): OOBE c monitor 11
I/InputMethodManagerService(  902): screenObserver, isScreenOn=false
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
I/InputMethodManagerService(  902): Disable input method client, pid=4406
D/NfcService( 1270): applyRouting -2
,V/KeyguardServiceDelegate(  902): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@41f6e740)
,V/KeyguardServiceDelegate(  902): **** SHOWN CALLED ****
D/PMS     (  902): acquireWL(41d428c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1270 1027 null
D/WIFI_ICON( 1118): WifiActivity: 3
D/PMN     (  902): wakingUp
D/PMS     (  902): acquireWL(425bf4a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/BatteryService(  902): n_update end
D/PMS     (  902): releaseWL(41d428c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  902): releaseWL(425bf4a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  902): No lock screen! windowToken=null
D/PMN     (  902): onScreenOn
,I/AlarmManager(  902): [AlarmQueuing] connectivity wifi: true
,D/HtcPowerSaver(  902): updateBatteryInfo
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/MtpService( 2388): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2388): [MTP][onReceive]-
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1861/1000)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1434/10028)
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/acms    ( 1861): Checking Certificates
,I/acms    ( 1861): Checking Developer Certificates
I/acms    ( 1861): Checking Application Certificates
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
D/GpsLocationProvider(  902): [handleMessage] UPDATE_NETWORK_STATE
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
D/GpsLocationProvider(  902): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  902): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  902): ignore wifi update if we are not in OPENING or CLOSING
,D/NfcService( 1270): applyRouting - 0
I/acms    ( 1861): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/ConnectivityHelper( 1286): [onReceive] WIFI(1): CONNECTED
I/acms    ( 1861): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1861): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1861): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1861): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1861): Updating next query delay: 75600000
I/mlserverapp( 1861): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1861): cancelACMSProgrammedChecks
,D/NfcService( 1270): applyRouting -2
,I/NetworkMonitor( 4473): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.htc.launcher (1286/10075)
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
D/PMS     (  902): acquireWL(42545da0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
D/PMS     (  902): releaseWL(42545da0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  902): acquireWL(42451350): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1270 1027 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.docs (4294/10100)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.google.android.music (4473/10154)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.musicenhancer (3900/10051)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/PMS     (  902): releaseWL(42451350): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/CaptivePortalTracker(  902): NoActiveNetworkState
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  902): DelayedCaptiveCheckState
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.docs (4294/10100)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/PMS     (  902): acquireWL(425a5470): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 902 1000 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
,W/Settings( 4631): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/PMS     (  902): runPSCheck
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/WirelessDisplayService(  902): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  902): releaseWL(425a5470): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
,D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/InputManager(  902): Cancel all due to getting PMS screen off broadcast
D/ConnectivityService(  902): getActiveNetworkInfo called by  (2388/10021)
,I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
W/ActivityManager(  902): Activity pause timeout for ActivityRecord{43266db8 u0 com.test.thalitest/.MainActivity t2 f}
,D/AlarmManager(  902): ACTION_SCREEN_ON
I/AlarmManager(  902): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  902): [AlarmQueuing] done recovering
I/AlarmManager(  902): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  902): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  902): startDataStallAlarm: tag=20351 delay=15s
,D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): SET_SCREEN_ON:On
I/wpa_supplicant( 1135): htc_wext_set_keepalive +
I/wpa_supplicant( 1135): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1135): getPrivFuncNum +	
I/wpa_supplicant( 1135): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1135): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1135): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,D/WifiNative-wlan0(  902):    returned true
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  902): acquireWL(42589f98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1240 10028 null
,D/PMS     (  902): releaseWL(42589f98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1135): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
I/FeedHostManager( 1286): [onResume]
I/FeedProviderManager( 1286): onResume
I/SocialFeedProvider( 1286): +onResume
I/SocialFeedProvider( 1286): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1286): -onResume
,D/GCM     ( 1360): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.launcher (1286/10075)
V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1360): [NET] getaddrinfo-, 1
,D/libc    ( 1360): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c896 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  902): acquireWL(42527a18): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1360 10028 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 0 by  (1360/10028)
D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=0,mActiveDefaultNetwork=1
,D/ConnectivityService(  902): handleInetConditionChange: starting a change hold
,I/ClockThread( 1118): stop update clock
D/PMS     (  902): releaseWL(42527a18): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/NetworkPolicy(  902): updateScreenOn: false
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=50 [2][1][0]
,D/AutoSetting( 1385): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (4631/10028)
,D/MobileConnectivityChangeReceiver( 4524): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
I/Adreno-EGL( 4631): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4631): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4631): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4631): Local Branch: 
I/Adreno-EGL( 4631): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4631): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4631):                  aa63bbd948f41d15fc72f585e
,D/MobileConnectivityChangeReceiver( 4524): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1385): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1385): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
D/AutoSetting( 1385): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1385): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.magazines (4557/10151)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 105
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1360): [NET] getaddrinfo_proxy-, success
D/PMS     (  902): releaseWL(41f0e230): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/PMS     (  902): acquireWL(44081b50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
D/PMS     (  902): releaseWL(44081b50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1783): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1783): onScreenOn: 1452155907358
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1783): onScreenOn: 1452155907358
,D/AutoSetting( 1385): receiver - intent: android.intent.action.USER_PRESENT
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 13.507MB for 1821008-byte allocation
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42279aa0
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
,W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42279aa0, eanble = 0, strlen(mName) = 91
,W/SensorService(  902): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  902): Listener[0] = com.htc.smartdim.sensor_eye@41d30c88
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMN     (  902): goingToSleep
,D/AutoSetting( 1385): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/CheckinTask( 1240): Sending checkin request (8956 bytes)
D/TetherSettings( 4190): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4190): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4190): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4190): Cust_ConnectToPC   : spcsc>false
D/        ( 4190): Cust_ConnectToPC   : IPT>true
,D/        ( 4190): Cust_ConnectToPC   : Singel_USB>false
,D/PMS     (  902): acquireWL(434e5978): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 902 1000 null
W/Settings( 4190): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/libc    ( 1240): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1240): [NET] getaddrinfo-,err=8
D/libc    ( 1240): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1240): [NET] getaddrinfo-, 1
,D/libc    ( 1240): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =af3b +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
E/SmartNS_Utility( 4190): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4190): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4190): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/FeedHostManager( 1286): [onPause]
,I/FeedProviderManager( 1286): onPause
,I/SocialFeedProvider( 1286): +onPause
I/SocialFeedProvider( 1286): -onPause
,I/FeedHostManager( 1286): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f54810
,I/PSReceiver( 4190): onReceive:android.intent.action.USER_PRESENT
D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_OFF
I/SmartNS_PSService( 4190): onReceive:android.intent.action.USER_PRESENT
,D/WifiDataStallTracker(  902): stopDataStallAlarm: current tag=20351 mDataStallAlarmIntent=PendingIntent{42391318: PendingIntentRecord{4263e568 android broadcastIntent}}
W/Settings( 4190): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4190):  defaultType:0
W/ContextImpl( 4190): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/AlarmManager(  902): ACTION_SCREEN_OFF
I/AlarmManager(  902): [AlarmQueuing] screen off now: 
I/AlarmManager(  902): [AlarmQueuing] data connection: true
I/AlarmManager(  902): [AlarmQueuing] wifi connection: true
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/PMS     (  902): acquireWL(435e9040): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 902 1000 null
D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): SET_SCREEN_ON:Off
I/wpa_supplicant( 1135): htc_wext_set_keepalive +
I/wpa_supplicant( 1135): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1135): getPrivFuncNum +	
I/wpa_supplicant( 1135): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1135): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1135): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1135): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1135): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 220
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1240): [NET] getaddrinfo_proxy-, success
D/Process (  902): killProcessQuiet, pid=4263
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
I/ActivityManager(  902): Killing 4263:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  902):    returned true
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  902): releaseWL(434e5978): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/NetworkPolicy(  902): updateScreenOn: false
I/ActivityManager(  902): Recipient 4263
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): releaseWL(435e9040): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,W/fb4a(:<default>):UserScope( 4493): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  902): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4681 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/fb4a(:<default>):UserScope( 4493): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=14 [7][1][0]
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0,
,D/ContactMessageStore( 1254): start background delete task...
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/ContactMessageStore( 1254): size: 0 , 0
D/ContactMessageStore( 1254): Background delete complete
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] getTotalRam: 1873 Mb
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
D/PMS     (  902): acquireWL(4361eeb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
D/PMS     (  902): releaseWL(4361eeb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  902): acquireWL(43fc7910): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4681 1000 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1783): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1783): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1783): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1783): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1783): onScreenOff
,D/AutoSetting( 1385): service - mHandler: cancel location update
,D/AutoSetting( 1385): service -           changes count: 0
,D/PMS     (  902): releaseWL(43fc7910): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4681): getMobilePolicyEnabled, result = true
D/Process (  902): killProcessQuiet, pid=4294
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 4294:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4681): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
D/WifiService(  902): New client listening to asynchronous messages
I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41d30c88
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 1
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d30c88, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 0
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d30c88, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41d30c88
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  902): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4243f8c0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4243f8c0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  902): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  902): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  902): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  902): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  902): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  902): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  902): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  902): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  902): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  902): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  902): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  902): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  902): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  902): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  902): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  902): 	at dalvik.system.NativeStart.main(Native Method)
,D/libc    ( 1240): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1240): [NET] getaddrinfo-,err=8
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 4294
,E/fb4a(:<default>):LocalFbBroadcastManager( 4493): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/PMS     (  902): releaseWL(43615378): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  902): acquireWL(440bc750): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4473 10154 null
,W/ContextImpl( 4473): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4473): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4473, uid=10154, userID:0
,I/MusicLeanback( 4473): Conditions not met for autocaching.
,I/MusicLeanback( 4473): Stop autocaching.
D/PMS     (  902): releaseWL(440bc750): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/PMS     (  902): acquireWL(433d7aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,D/PMS     (  902): releaseWL(433d7aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  902): getNetworkInfo networkType=9 called by com.google.android.gms (1240/10028)
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
,D/ConnectivityService(  902): getNetworkInfo networkType=0 called by com.google.android.gms (1240/10028)
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=35 [20][7][0]
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1240): awaiting user notification for token
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41e604e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 1 11 3 12
,I/CheckinTask( 1240): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1240): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  902): releaseWL(44066488): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1240): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bbd9f0 that was originally bound here
E/ActivityThread( 1240): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bbd9f0 that was originally bound here
E/ActivityThread( 1240): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1240): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1240): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1240): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1240): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1240): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1240): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1240): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1240): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1240): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1240): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1240): 	at bks.a(SourceFile:298)
E/ActivityThread( 1240): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1240): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1240): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1360): GCM config loaded
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1360): [NET] getaddrinfo-, 1
,D/libc    ( 1360): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =b595 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 1360): [NET] getaddrinfo_proxy-, success
D/PMS     (  902): acquireWL(4356c658): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1360 10028 null
,D/libc    (  902): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a058 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 2,
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  902): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  902): Find DNS Address www.htc.com/104.81.130.175,
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4,
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  902): acquireWL(437e53d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
D/PMS     (  902): releaseWL(437e53d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1360): Connected
D/PMS     (  902): acquireWL(43067b68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  902): releaseWL(4356c658): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  902): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  902): releaseWL(43067b68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  902): acquireWL(43271fd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
,D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1360): Message class mpf
D/ConnectivityService(  902): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  902): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/PMS     (  902): acquireWL(434da290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,D/PMS     (  902): releaseWL(43271fd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  902): releaseWL(434da290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ContactMessageStore( 1254): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1254): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4557): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  902): acquireWL(437cc308): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
,D/PMS     (  902): acquireWL(437df238): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1434 10028 null
,D/PMS     (  902): releaseWL(437cc308): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  902): releaseWL(437df238): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  902): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  902): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=27 [11][3][0]
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
,D/Process (  902): killProcessQuiet, pid=4317
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 4317:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 4317
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1495): service - handleMessage() stop self
,D/AutoSetting( 1495): service - onDestroy() END
,D/Process (  902): killProcessQuiet, pid=4334
,I/ActivityManager(  902): Killing 4334:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1495): service - handleMessage() quit looper
,I/ActivityManager(  902): Recipient 4334
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  902): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  902): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  902): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  902): Activity destroy timeout for ActivityRecord{43266db8 u0 com.test.thalitest/.MainActivity t2 f}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{4365ab68 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  902): acquireWL(433e77b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(433e77b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4393b8a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
,D/PMS     (  902): acquireWL(43b77ce0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 0 by  (1360/10028)
D/PMS     (  902): releaseWL(43b77ce0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=0,mActiveDefaultNetwork=1
,D/ConnectivityService(  902): handleInetConditionChange: starting a change hold
,D/PMS     (  902): releaseWL(4393b8a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/ConnectivityService(  902): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/ConnectivityService(  902): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=25 [8][2][0]
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0],
,D/AutoSetting( 1385): service - mHandler: update timezone
,D/AutoSetting( 1495): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  902): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1495): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1495): service - onCreate()
W/ActivityManager(  902): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1495): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1495): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
,D/DotMatrix( 1562): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1495): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1495): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1495): service - mHandler: update timezone
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1495): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1495): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1495): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1495): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41bbfc00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 7 3 11
,D/AutoSetting( 1385): service - handleMessage() stop self
,D/AutoSetting( 1385): service - handleMessage() quit looper
,D/AutoSetting( 1385): service - onDestroy() END
,D/PMS     (  902): acquireWL(4253dfb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10028}
,V/AlarmManager(  902): sending alarm PendingIntent{4203bc28: PendingIntentRecord{42480110 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141908, Int=0
,V/AlarmManager(  902): sending alarm PendingIntent{4246b490: PendingIntentRecord{42409b30 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142060, Int=0
,D/GpsLocationProvider(  902): ALARM_XTRA_TIMEOUT
D/PMS     (  902): acquireWL(434d7a98): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
D/PMS     (  902): releaseWL(4253dfb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43622040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43622040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/GpsLocationProvider(  902): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  902): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  902): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d318 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/PMS     (  902): acquireWL(440798c8): PARTIAL_WAKE_LOCK  Icing 0x1 1240 10028 null
,D/PMS     (  902): releaseWL(440798c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(43fd98b0): PARTIAL_WAKE_LOCK  Icing 0x1 1240 10028 null
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  902): [NET] getaddrinfo_proxy-, success
I/global  (  902): call createSocket() return a new socket.
D/libc    (  902): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/PMS     (  902): releaseWL(43fd98b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  902): acquireWL(43f1a938): PARTIAL_WAKE_LOCK  Icing 0x1 1240 10028 null
,D/PMS     (  902): releaseWL(43f1a938): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/GpsLocationProvider(  902): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  902): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  902): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  902):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  902): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  902): acquireWL(4362a728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=144252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4362a728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): releaseWL(434d7a98): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  902): killProcessQuiet, pid=3900
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3900:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3900
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{430394e0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  902): acquireWL(42608df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41d1e0d8: PendingIntentRecord{4241edc8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=168255, Int=0
,D/PMS     (  902): acquireWL(425323f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 902 1000 null
D/PMS     (  902): releaseWL(42608df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/PMS     (  902): acquireWL(421cd230): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 902 1000 null
,D/PMS     (  902): releaseWL(425323f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  902): releaseWL(421cd230): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1495): service - handleMessage() stop self
,D/AutoSetting( 1495): service - onDestroy() END
,D/AutoSetting( 1495): service - handleMessage() quit looper
,D/Process (  902): killProcessQuiet, pid=4352
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 4352:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 4352
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1254): switchBindHtcMsgCursor: null
,D/PMS     (  902): acquireWL(435800b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end,
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): releaseWL(435800b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(4379be70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/BatteryService(  902): n_update end
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(4379be70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4342d3b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=204253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4342d3b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(425e3790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10026}
,V/AlarmManager(  902): sending alarm PendingIntent{4379c130: PendingIntentRecord{437b15e0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229365, Int=0
,I/ActivityManager(  902): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4734 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  902): sending alarm PendingIntent{41f18ed0: PendingIntentRecord{41f0b0a8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452156016883, Int=10800000
,D/PMS     (  902): releaseWL(425e3790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.aurora (4734/10047)
,D/Process (  902): killProcessQuiet, pid=4367
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 4367:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 4367
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,D/PMS     (  902): acquireWL(424184a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10026}
,V/AlarmManager(  902): sending alarm PendingIntent{42460bf0: PendingIntentRecord{437b15e0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231654, Int=0
,D/PMS     (  902): releaseWL(424184a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(42036650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(42036650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(42676040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=264252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42676040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(44019d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(44019d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43647438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=324253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43647438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1360): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1360): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1360): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1360): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1360): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1360): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1360): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1360): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41e7ee40 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4130): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4130): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4130): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4130): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4130): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4130): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4130): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4130): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1118): com.google.android.gms 4 15 4 12
,D/libc    ( 4130): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4130): [NET] getaddrinfo-,err=8
D/libc    ( 4130): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4130): [NET] getaddrinfo-, 1
,D/libc    ( 4130): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ae00 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 69
D/libc    (  365): [NET]res_nsend:resplen=87
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4130): [NET] getaddrinfo_proxy-, success
I/global  ( 4130): call createSocket() return a new socket.
D/libc    ( 4130): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4130): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4130): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4,
,D/libc    ( 4130): [NET] getaddrinfo-,err=8,
,D/PMS     (  902): acquireWL(433c7458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(433c7458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(44130db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(44130db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(4252ac68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=384252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4252ac68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process ( 4406): killProcess, pid=4406
,D/Process ( 4406): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  902): Disable input method client, pid=4406
,I/ActivityManager(  902): Recipient 4406
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  902): channel '420b3ef8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  902): channel '420b3ef8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  902): Attempted to unregister already unregistered input channel '420b3ef8 com.test.thalitest.MainActivity (s)'
I/ActivityManager(  902): Process com.test.thalitest (pid 4406) has died.
D/WifiService(  902): Client connection lost with reason: 4
I/WindowManager(  902): WINDOW DIED Window{420b3ef8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/WindowManager(  902): Failed looking up window
W/WindowManager(  902): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@435339d8 does not exist
W/WindowManager(  902): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  902): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  902): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  902): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  902): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  902): WIN DEATH: null
,D/PMS     (  902): acquireWL(433eaf30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10026}
,V/AlarmManager(  902): sending alarm PendingIntent{43a080b8: PendingIntentRecord{42944038 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=411489, Int=300000
,V/AlarmManager(  902): sending alarm PendingIntent{433bfd20: PendingIntentRecord{43856fb0 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1452156154648, Int=0
,D/PMS     (  902): releaseWL(433eaf30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 1240): No account for auth token provided
,D/libc    ( 1240): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1240): [NET] getaddrinfo-,err=8
D/libc    ( 1240): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1240): [NET] getaddrinfo-, 1
,D/libc    ( 1240): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =74ec +++++
,D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1240): [NET] getaddrinfo_proxy-, success
I/global  ( 1240): call createSocket() return a new socket.
D/libc    ( 1240): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1240): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 1240): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1240): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(433ec278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1118): closing low battery warning: level=100
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(433ec278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4344ebb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4344ebb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43f0f6a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=444253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43f0f6a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(4356c718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4356c718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(43f8dd80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(43f8dd80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42fb1e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=504253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42fb1e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(42694450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42694450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
,I/HtcPowerSaver(  902): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4357dc98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(4357dc98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42613318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=564253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42613318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1135): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1135): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1135): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1135): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1135): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1135): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1135): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1135): nl80211: Disconnect event
I/wpa_supplicant( 1135): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1135): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  902): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  902): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  902): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  902): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  902): Enter handleNetworkDisconnect
I/wpa_supplicant( 1135): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1135): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1135): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1135): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 0
E/wpa_supplicant( 1135): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1135): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8586bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1135):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1135): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1135): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1135): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1135): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/w,pa_supplicant( 1135): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  902): interfaceLinkStateChanged wlan0, false
D/Tethering(  902): interfaceStatusChanged wlan0, false
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): Power_Mode_Type mode = 0
I/wpa_supplicant( 1135): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 61
D/Tethering(  902): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  902): interfaceLinkStateChanged wlan0, false
,D/Tethering(  902): interfaceStatusChanged wlan0, false
D/Tethering(  902): [isWifi] getHotspotEnabled: false
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  902): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  902): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  902):    returned true
D/libc    (  902): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  902): [RunningState] Stop DHCP
,D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  902): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiStateMachine(  902): Exit handleNetworkDisconnect
D/WifiPerfLock(  902): release()
,D/WifiStateMachine(  902): PerfLock released for exiting ConnectedState
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  902): stopDataStallAlarm: current tag=20352 mDataStallAlarmIntent=null
D/ConnectivityService(  902): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  902): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  902): Provision feature enable=false
D/ConnectivityService(  902): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): Power_Mode_Type mode = 0
I/wpa_supplicant( 1135): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  902): isAvailable+-
D/UsbnetStateTracker(  902): reconnect
D/UsbnetStateTracker(  902): isAvailable+-
D/WifiNative-wlan0(  902):    returned true
,D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 2
D/PMS     (  902): acquireWL(44060190): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 902 1000 null
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  902): default: reconnect()
D/MDST    (  902): default: setTeardownRequested(false)
D/MDST    (  902): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  902): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  902):    returned true
D/WifiP2pService(  902): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  902): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  902): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  902): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WISPrService( 4190): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4190): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  902): doBoolean: SET pno 1
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/ConnectivityService(  902): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  902): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  902): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1135): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1135): nl80211: Event message available
,D/wpa_supplicant( 1135): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  902):    returned true
,D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
W/ConnectivityService(  902): Exception trying to remove a route: java.lang.IllegalStateException: command '56 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 56 Failed to remove route from default table (No such process)'
D/ConnectivityService(  902): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  902): Exception trying to remove a route: java.lang.IllegalStateException: command '57 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 57 Failed to remove route from default table (No such process)'
D/ConnectivityService(  902): handleConnectivityChange: resetting
,D/ConnectivityService(  902): resetConnections(wlan0, 3)
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  902): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4190): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  902): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4190): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] entry_id:1   entry:0xb8188410  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8188830  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8188108  removed 
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,D/ConnectivityService(  902): flush DNS cache for net 1(wlan0)
D/libc    (  365): [NET] entry_id:3   entry:0xb8187fd8  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb81885b8  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/Nat464Xlat(  902): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  902): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  902): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  902): acquireWL(43459740): PARTIAL_WAKE_LOCK  NetworkStats 0x1 902 1000 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
,D/ConnectivityService(  902): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/wpa_supplicant( 1135): wpa_supplicant_scan enter
I/wpa_supplicant( 1135): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1135): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1135): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1135): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WirelessDisplayService(  902): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  902): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
,D/WifiStateMachine(  902): startScan Pid: 902 Uid 1000
,D/WifiNative-wlan0(  902): doBoolean: SET pno 0
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1135): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1135): wpa_supplicant_scan enter
D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: SCAN
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): wpa_supplicant_scan enter
I/wpa_supplicant( 1135): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1135): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1135): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1135): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1135): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1135): Failed to initiate AP scan
,I/wpa_supplicant( 1135): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/BatSI   (  902): WIFI scan started for: 450a0300 uid:1000
I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiNative-wlan0(  902):    returned true
,D/PMS     (  902): releaseWL(43459740): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  902): mActiveDefaultNetwork: -1
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  902): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
,D/GpsLocationProvider(  902): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  902): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  902): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  902): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/PMS     (  902): acquireWL(43443718): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
,D/PMS     (  902): releaseWL(43443718): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
I/wpa_supplicant( 1135): wpa_supplicant_scan enter
I/wpa_supplicant( 1135): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1135): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1135): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1135): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1135): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1135): Failed to initiate AP scan
I/wpa_supplicant( 1135): Failed to initiate AP scan, Failed_to_scan_counter:2
,D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  902): DelayedCaptiveCheckState
D/CaptivePortalTracker(  902): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  902): NoActiveNetworkState
,I/ConnectivityHelper( 1286): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1434/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.htc.launcher (1286/10075)
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1861/1000)
,D/Tethering(  902): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,I/NetworkMonitor( 4473): type=WIFI subType= reason=null isConnected=false
V/Tethering(  902): bSetPropertyMultiRAB:false
D/Tethering(  902): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  902): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  902): ipv4Default null
I/Tethering(  902): No IPv4 upstream interface, giving up.
,D/Tethering(  902): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.google.android.music (4473/10154)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (2388/10021)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/PMS     (  902): acquireWL(440195e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1240 10028 null
,D/PMS     (  902): acquireWL(42e0e080): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1240 10028 null
,D/PMS     (  902): releaseWL(440195e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,D/GCM     ( 1360): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/PMS     (  902): releaseWL(42e0e080): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,D/AutoSetting( 1385): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4524): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4524): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
,D/AutoSetting( 1385): Util - no network available!
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
,D/AutoSetting( 1385): service - onCreate()
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.magazines (4557/10151)
,D/AutoSetting( 1385): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1385): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  902): request 4248db98 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  902): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1385): service - mHandler: cancel location update
,D/AutoSetting( 1385): service -           changes count: 0
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 15.215MB for 1821008-byte allocation
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
,D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 16.947MB for 1821008-byte allocation
,I/wpa_supplicant( 1135): wpa_supplicant_scan enter
I/wpa_supplicant( 1135): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1135): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1135): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1135): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1135): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1135): Failed to initiate AP scan
,I/wpa_supplicant( 1135): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1135): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1135): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1135): nl80211: Survey data missing
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1135): Sorted scan results
I/wpa_supplicant( 1135): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
D/wpa_supplicant( 1135): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1135): Add randomness: count=21 entropy=0
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1135): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1135): wpa_supplicant_pick_network+
I/wpa_supplicant( 1135): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1135): Selecting BSS from priority group 1
I/wpa_supplicant( 1135): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1135): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1135): No APs found - clear blacklist and try again
E/wpa_supplicant( 1135): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1135): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1135): Selecting BSS from priority group 1
I/wpa_supplicant( 1135): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1135): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1135): clear disabled list - type=1
I/wpa_supplicant( 1135): No suitable network found
W/wpa_supplicant( 1135): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1135): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1135): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1135): nl80211: Survey data missing
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1135): Sorted scan results
I/wpa_supplicant( 1135): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
D/wpa_supplicant( 1135): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1135): Add randomness: count=22 entropy=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1135): WPS: AP[1] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1135): wpa_supplicant_pick_network+
I/wpa_supplicant( 1135): clear disabled list - type=1
I/wpa_supplicant( 1135): No suitable network found
W/wpa_supplicant( 1135): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1135): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  902): doBoolean: SET pno 1,
D/WifiMonitor(  902): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1135): CTRL_IFACE SET 'pno'='1',
D/WifiP2pService(  902): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 75
,D/wpa_supplicant( 1135): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  902):    returned true
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  902): doString: LIST_DONGLES
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1135): reply (238) for get BSS: id=3
I/wpa_supplicant( 1135): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1135): freq=2412
I/wpa_supplicant( 1135): level=-52
I/wpa_supplicant( 1135): tsf=0000000108151124
I/wpa_supplicant( 1135): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1135): ssid=NG700
I/wpa_supplicant( 1135): ====
I/wpa_supplicant( 1135): id=6
I/wpa_supplicant( 1135): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1135): freq=5220
I/wpa_supplicant( 1135): level=-54
I/wpa_supplicant( 1135): tsf=0000000578912060
I/wpa_supplicant( 1135): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1135): ssid=NG7005g
I/wpa_supplicant( 1135): ####
,D/WirelessDisplayService(  902): getDiscoveryDongleList
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (2) end of scan result ==
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/WifiStateMachine(  902): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 108151124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 5220, timestamp: 578912060, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 2 to mScanResults
D/BatSI   (  902): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1135): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1135): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1135): nl80211: Survey data missing
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1135): Sorted scan results
I/wpa_supplicant( 1135): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
D/wpa_supplicant( 1135): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1135): Add randomness: count=23 entropy=2
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1135): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1135): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1135): wpa_supplicant_pick_network+
I/wpa_supplicant( 1135): Selecting BSS from priority group 1
I/wpa_supplicant( 1135): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1135): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1135): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1135):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1135):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
I/wpa_supplicant( 1135): Start print parameters
I/wpa_supplicant( 1135): wpa_s->wpa_state is 3
I/wpa_supplicant( 1135): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1135): isConcurrentMode() is 0
I/wpa_supplicant( 1135): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1135): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1135): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1135): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1135): wpa_s->reassociate is 0
I/wpa_supplicant( 1135): wpa_s->is_screen_on 0
I/wpa_supplicant( 1135): wpa_s->ifname wlan0
I/wpa_supplicant( 1135): End print parameters
I/wpa_supplicant( 1135): selected network = 3
D/wpa_supplicant( 1135): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85884e8  current_ssid=0x0
D/wpa_supplicant( 1135): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1135): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1135): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1135): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1135): check if in concurrent case
I/wpa_supplicant( 1135): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1135): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1135): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1135): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1135): RSN: PMKSA cache search - network_ctx=0xb85884e8 try_opportunistic=0
D/wpa_supplicant( 1135): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1135): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1135): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1135): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1135): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1135): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 6
D/wp,a_supplicant( 1135): nl80211: Unsubscribe mgmt frames handle 0xb8587718 (mode change)
D/wpa_supplicant( 1135): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8587718
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Register frame type=0xd0 nl_handle=0xb8587718,
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1135): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1135):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1135):   * freq=2412
D/wpa_supplicant( 1135):   * Auth Type 0
D/wpa_supplicant( 1135):   * WPA Versions 0x2
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1135): nl80211: Connect request send successfully
D/wpa_supplicant( 1135): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18,
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSID
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1135): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1135): reply (238) for get BSS: id=3
I/wpa_supplicant( 1135): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1135): freq=2412
I/wpa_supplicant( 1135): level=-53
I/wpa_supplicant( 1135): tsf=0000000580891973
I/wpa_supplicant( 1135): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1135): ssid=NG700
I/wpa_supplicant( 1135): ====
I/wpa_supplicant( 1135): id=6
I/wpa_supplicant( 1135): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1135): freq=5220
I/wpa_supplicant( 1135): level=-54
I/wpa_supplicant( 1135): tsf=0000000578912060
I/wpa_supplicant( 1135): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1135): ssid=NG7005g
I/wpa_supplicant( 1135): ####
,D/WirelessDisplayService(  902): getDiscoveryDongleList
,D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (2) end of scan result ==
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  902): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 580891973, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 5220, timestamp: 578912060, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 2 to mScanResults
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/wpa_supplicant( 1135): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1135): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1135): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1135): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1135): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 1135): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1135): nl80211: if_removed already cleared - ignore event
,D/Tethering(  902): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1135): nl80211: Connect event
D/wpa_supplicant( 1135): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1135): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1135): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1135): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 1135): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1135): Add randomness: count=24 entropy=3
I/wpa_supplicant( 1135): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1135): TDLS: Remove peers on association
D/wpa_supplicant( 1135): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1135): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1135): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1135): EAPOL: SUPP_PAE entering state CONNECTING
,D/wpa_supplicant( 1135): EAPOL: enable timer tick
D/wpa_supplicant( 1135): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1135): htc_wext_set_keepalive +
I/wpa_supplicant( 1135): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1135): getPrivFuncNum +	
I/wpa_supplicant( 1135): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1135): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1135): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1135): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1135): Get randomness: len=32 entropy=4
D/Tethering(  902): interfaceStatusChanged wlan0, false
D/Tethering(  902): [isWifi] getHotspotEnabled: false
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  902): interfaceLinkStateChanged wlan0, true
D/Tethering(  902): interfaceStatusChanged wlan0, true
,D/WifiMonitor(  902): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  902): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/Tethering(  902): [isWifi] getHotspotEnabled: false
D/HTCRequest(  902): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  902): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  902): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  902): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  902): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  902): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
,I/wpa_supplicant( 1135): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb85879f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1135):    addr=c0:ff:d4:d3:aa:48
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  902): Enter handleAssociatedWithEvent
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 11
D/WifiStateMachine(  902): Associated
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1135): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1135): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f35b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1135):    broadcast key
,D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1135): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,E/wpa_supplicant( 1135): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1135): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1135): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1135): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  902): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1135): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1135): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1135): set send_ind_to_ndc = 0
,I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1135): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1135): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1135): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1135): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1135): EAPOL: SUPP_BE entering state SUCCESS
,D/wpa_supplicant( 1135): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1135): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1135): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1135): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1135): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1135): EAPOL authentication completed successfully
I/wpa_supplicant( 1135): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1135): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1135): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1135): nl80211: if_removed already cleared - ignore event
D/Tethering(  902): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  902): interfaceStatusChanged wlan0, true
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/Tethering(  902): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  902): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  902): Exit handleAssociatedWithEvent
D/WifiStateMachine(  902): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  902): updateConnectedAP...
D/WifiApDatabaseHandler(  902): updateConnectedAP...
,D/WifiStateMachine(  902): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  902): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  902): This record is existed, only update it...
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  902): updateConnectedAP...,
,D/WifiStateMachine(  902): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false,
,D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  902): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  902): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  902): This record is existed, only update it...
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  902): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  902): Provision feature enable=false
D/ConnectivityService(  902): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4190): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4190): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
,D/WifiNative-wlan0(  902): doBoolean: SET pno 0
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1135): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1135): nl80211: Event message available
D/wpa_supplicant( 1135): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  902):    returned true
,D/DhcpStateMachine(  902): [StoppedState] Start DHCP
,D/WifiStateMachine(  902): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): Power_Mode_Type mode = 1
I/wpa_supplicant( 1135): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  902):    returned true
,D/WifiNative-wlan0(  902): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1135): nl80211: Event message available
D/WifiStateMachine(  902): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  902): acquireWL(4335ec38): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 902 1000 null
,D/WifiStateMachine(  902): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/wpa_supplicant( 1135): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1135): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  902):    returned null
,E/WifiStateMachine(  902): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  902): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  902):    returned null
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiP2pService(  902): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42629548 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42629548 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  902): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
,D/wpa_supplicant( 1135): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1135): EAPOL: disable timer tick
,D/libc    (  902): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  902): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1135): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1135): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12,
D/WifiNative-wlan0(  902):    returned true
D/WifiStateMachine(  902): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/WifiP2pService(  902): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  902): releaseWL(4335ec38): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=66 [3][2][0]
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1135): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
D/WifiStateMachine(  902): gateway: /192.168.1.1
,D/WifiNative-wlan0(  902): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1135): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1135): htc_wext_set_keepalive +
I/wpa_supplicant( 1135): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1135): getPrivFuncNum +	
I/wpa_supplicant( 1135): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1135): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1135): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1135): htc_wext_set_keepalive gateway addr = c0a80101
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1135): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  902):    returned true
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  902): VerifyingLinkState enter
D/WifiStateMachine(  902): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  902): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  902): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  902): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  902): Provision feature enable=false
,D/WifiWatchdogStateMachine(  902): WAN detection
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  902): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false,
V/ConnectivityService(  902): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  902): default: teardown()
D/MDST    (  902): default: setTeardownRequested(true)
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  902): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  902): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/MDST    (  902): default: setTeardownRequested(true)
,D/ConnectivityService(  902): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WISPrService( 4190): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  902): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  902): syncGetConfiguredNetworks
E/ConnectivityService(  902): Unexpected mtu value: android.net.wifi.WifiStateTracker@423b2e88
D/ConnectivityService(  902): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  902): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  902): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  902): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  902): handleConnectivityChange: resetting
D/Nat464Xlat(  902): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  902): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  902): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  902): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  902): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  902): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  902): acquireWL(4341ab60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 902 1000 null
D/WirelessDisplayService(  902): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  902):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
,D/PMS     (  902): acquireWL(425d5908): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1240 10028 null
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/PMS     (  902): releaseWL(4341ab60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  902): acquireWL(42b7b120): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1240 10028 null
D/PMS     (  902): releaseWL(425d5908): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,I/CheckinService( 1240): Preparing to send checkin request
,I/EventLogService( 1240): Accumulating logs since 1452155905806
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1240): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1240): Using GMS GoogleHttpClient
,D/ConnectivityService(  902): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  902): getNetworkInfo networkType=9 called by com.google.android.gms (1240/10028)
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  902): getNetworkInfo networkType=0 called by com.google.android.gms (1240/10028)
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 1240): awaiting user notification for token
D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41e75980 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 3 10 2 12
,I/Adreno-EGL( 4631): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4631): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4631): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4631): Local Branch: 
I/Adreno-EGL( 4631): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4631): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4631):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4631): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4631): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4631): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4631): Local Branch: 
I/Adreno-EGL( 4631): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4631): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4631):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4631): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (4631/10028)
,I/Adreno-EGL( 4631): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4631): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4631): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4631): Local Branch: 
I/Adreno-EGL( 4631): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4631): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4631):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  902): releaseWL(44060190): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  902): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  902): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/CaptivePortalTracker(  902): NoActiveNetworkState
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
I/ConnectivityHelper( 1286): [onReceive] WIFI(1): CONNECTED
,V/Tethering(  902): bSetPropertyMultiRAB:false
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/Tethering(  902): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.htc.launcher (1286/10075)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
I/Tethering(  902): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  902): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/acms    ( 1861): Checking Certificates
I/Tethering(  902): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  902): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  902): Found interface wlan0
I/acms    ( 1861): Checking Developer Certificates
D/Tethering(  902): TetherMasterSM: InitialState processMessage what=3
I/acms    ( 1861): Checking Application Certificates
I/acms    ( 1861): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1861): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
,I/acms    ( 1861): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1861): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1861): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1861): Updating next query delay: 75600000
I/mlserverapp( 1861): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1861): cancelACMSProgrammedChecks
,I/CheckinTask( 1240): Sending checkin request (8959 bytes)
D/CaptivePortalTracker(  902): DelayedCaptiveCheckState
D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/NetworkMonitor( 4473): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1861/1000)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.google.android.music (4473/10154)
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1434/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
D/PMS     (  902): acquireWL(41dbac68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/libc    ( 1240): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1240): [NET] getaddrinfo-,err=8
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
D/libc    ( 1240): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    ( 1240): [NET] getaddrinfo-, 1
D/libc    ( 1240): [NET] getaddrinfo_proxy+
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =b214 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/PMS     (  902): acquireWL(43b55310): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 902 1000 null
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=100 [1][1][0]
,D/GpsLocationProvider(  902): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  902): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  902): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  902): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  902): releaseWL(43b55310): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/PMS     (  902): releaseWL(41dbac68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (2388/10021)
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4493/10026)
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 297
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1240): [NET] getaddrinfo_proxy-, success
,D/PMS     (  902): acquireWL(433c18c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1240 10028 null
,D/PMS     (  902): releaseWL(433c18c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1360): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1360): [NET] getaddrinfo-, 1
,D/libc    ( 1360): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9392 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  902): acquireWL(41fdb5a8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1360 10028 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
D/libc    (  365): [NET] NOT IN CACHE
,D/AutoSetting( 1385): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4524): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1385): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/MobileConnectivityChangeReceiver( 4524): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1385): service - onStartCommand() screen is off, don't request location
D/libc    ( 1240): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1240): [NET] getaddrinfo-,err=8
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
D/AutoSetting( 1385): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1385): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.magazines (4557/10151)
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=50 [6][3][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1360): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/PMS     (  902): acquireWL(43a94e10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,D/PMS     (  902): releaseWL(43a94e10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1360): Connected
D/PMS     (  902): acquireWL(43f10688): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  902): releaseWL(41fdb5a8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  902): handleInetConditionChange: starting a change hold
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  902): releaseWL(43f10688): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  902): acquireWL(435d4fb8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
,D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1360): Message class mpf
D/ConnectivityService(  902): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  902): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/PMS     (  902): releaseWL(435d4fb8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  902): acquireWL(433f9028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,D/PMS     (  902): releaseWL(433f9028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  902): acquireWL(43589bd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,D/PMS     (  902): releaseWL(43589bd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  902): getNetworkInfo networkType=9 called by com.google.android.gms (1240/10028)
,D/ConnectivityService(  902): getNetworkInfo networkType=0 called by com.google.android.gms (1240/10028)
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1135): environment dirty rate=12 [16][2][0]
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1240): awaiting user notification for token
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41e5a6e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 2 10 3 12
,I/CheckinTask( 1240): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1240): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1240/10028)
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  902): releaseWL(42b7b120): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1240): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b32158 that was originally bound here
E/ActivityThread( 1240): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b32158 that was originally bound here
E/ActivityThread( 1240): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1240): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1240): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1240): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1240): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1240): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1240): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1240): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1240): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1240): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1240): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1240): 	at bks.a(SourceFile:298)
E/ActivityThread( 1240): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1240): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1240): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1360): GCM config loaded
,D/ConnectivityService(  902): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  902): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
,D/libc    (  902): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c22c +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  902): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  902): Find DNS Address www.htc.com/104.81.130.175,
,D/WifiStateMachine(  902): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  902): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{43366b88 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/CaptivePortalTracker(  902): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  902): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  902): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  902): acquireWL(4353c630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4353c630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  902): acquireWL(435b0f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(435b0f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1385): service - handleMessage() stop self
,D/AutoSetting( 1385): service - mHandler: update timezone
,D/AutoSetting( 1495): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1495): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1385): service - handleMessage() quit looper
,D/AutoSetting( 1495): service - onCreate()
,D/AutoSetting( 1385): service - onDestroy() END
W/ActivityManager(  902): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  902): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1495): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1495): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/DotMatrix( 1562): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1495): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1495): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1495): service - mHandler: update timezone
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1495): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1495): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1495): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1495): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41a98fe8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 1 7 3 11
,D/ContactMessageStore( 1254): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1254): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1254): sku_id=99
D/ContactMessageStore( 1254): start background delete task...
,D/ContactMessageStore( 1254): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1254): size: 0 , 0
,D/ContactMessageStore( 1254): Background delete complete
,D/PMS     (  902): acquireWL(440798c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=624252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(440798c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(44062680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10028}
,V/AlarmManager(  902): sending alarm PendingIntent{435ab840: PendingIntentRecord{42633c68 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452156347596, Int=1800000
,D/PMS     (  902): acquireWL(43ffc810): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1240 10028 null
,V/AlarmManager(  902): sending alarm PendingIntent{43f8e448: PendingIntentRecord{41ffdb78 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452156420690, Int=0
,D/PMS     (  902): releaseWL(44062680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  902): acquireWL(43f95ae0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1240 10028 null
,D/PMS     (  902): releaseWL(43ffc810): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/EventLogService( 1240): Aggregate from 1452156378023 (log), 1452154547490 (data)
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  902): releaseWL(43f95ae0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4130): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4130): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4130): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4130): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4130): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{4256a3c8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  902): acquireWL(4211ec90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10073}
,V/AlarmManager(  902): sending alarm PendingIntent{42663610: PendingIntentRecord{43f5d0e8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452156435894, Int=0
,D/PMS     (  902): releaseWL(4211ec90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4130): [1] 5.onFinished: Installation state replication succeeded.
,D/AutoSetting( 1495): service - handleMessage() stop self
,D/AutoSetting( 1495): service - onDestroy() END
,D/AutoSetting( 1495): service - handleMessage() quit looper
,D/PMS     (  902): acquireWL(425d0230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(425d0230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(424badf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/PMS     (  902): releaseWL(424badf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(433bf580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=684253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(433bf580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43409378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(43409378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43670f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43670f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(42c5ad78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=744253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42c5ad78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4252b080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10026}
,V/AlarmManager(  902): sending alarm PendingIntent{43a080b8: PendingIntentRecord{42944038 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=711489, Int=300000
,V/AlarmManager(  902): sending alarm PendingIntent{41d81c48: PendingIntentRecord{423bd640 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786463, Int=0
,D/PMS     (  902): releaseWL(4252b080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  902): Done.
,D/ConnectivityService(  902): Setting timer for 720seconds
,D/PMS     (  902): acquireWL(4250f6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4250f6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  902): updateBatteryInfo
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42c5a6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=804252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42c5a6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(42443a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(42443a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43524828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(43524828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43f40c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=864253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43f40c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(433aac68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
I/BatteryService(  902): n_update end
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): releaseWL(433aac68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(41fc74c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(41fc74c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43532bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=924253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43532bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(424b6f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(424b6f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(432152f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=984253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(432152f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(424454b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{420442e8: PendingIntentRecord{4246ad30 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452156737384, Int=900000
,V/AlarmManager(  902): sending alarm PendingIntent{429fde40: PendingIntentRecord{4343a938 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452156807723, Int=0
,W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4681): call getInstance()
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4681): MY_DEBUG = false
D/PMS     (  902): acquireWL(42802a28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4681 1000 null
D/PMS     (  902): releaseWL(424454b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4681): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4681): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4681): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4681): SettingOnTime = 1452214800000, randomSettingOnTime = 1452214771000
,D/SmartSyncScreenOnOffTimeReceiver( 4681): SettingOffTime = 1452211200000, randomSettingOffTime = 1452212810000
,D/SmartSyncScreenOnOffTimeReceiver( 4681): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4681): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4681): bNightModeTurnOffOnce = false
,D/PMS     (  902): releaseWL(42802a28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/PMS     (  902): acquireWL(433b0458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(433b0458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43fd0be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1044253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43fd0be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/PMS     (  902): acquireWL(429c6660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
I/BatteryService(  902): n_update end
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): releaseWL(429c6660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4190): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4190): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4190): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4190): Cust_ConnectToPC   : spcsc>false
D/        ( 4190): Cust_ConnectToPC   : IPT>true
,D/        ( 4190): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4190): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4190): Index of the first 1 = 3
W/ContextImpl( 4190): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
W/Settings( 4190): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4190): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4190): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4190): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4190): [ACC]android_networking:tethering_guard_support=false
,W/ContextImpl( 4190): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(433e7d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1104253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(433e7d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43f140a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): releaseWL(43f140a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(435204b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(435204b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4379e948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1164253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4379e948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43f24de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43f24de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43bcdab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43bcdab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  902): acquireWL(435315a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1224253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(435315a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(434be250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(434be250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  902): updateBatteryInfo
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43b7ee10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43b7ee10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
,I/HtcPowerSaver(  902): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(430449b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1284253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(430449b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4360b5f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(4360b5f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(433cf240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(433cf240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(435560c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1344252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(435560c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(424db020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(424db020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  902): << updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(435a3db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(435a3db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
,D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(44017a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1404252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(44017a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(44097d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
,D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  902): releaseWL(44097d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43f1c238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43f1c238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  902): updateBatteryInfo
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4379ed48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1464253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4379ed48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4370e8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(4370e8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(435863b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
I/BatteryService(  902): n_update end
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(435863b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43572c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1524252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43572c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43561200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): releaseWL(43561200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4348fdb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1584253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4348fdb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4348e4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4348e4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(433d2e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(433d2e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42f50768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1644252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42f50768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(42f2b708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(42f2b708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42600db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42600db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(4248fb98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1704252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4248fb98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4237d298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4237d298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  902): runPSCheck
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(41a82748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(41a82748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
,D/PowerUI ( 1118): closing low battery warning: level=100
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(41af6998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1764252, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(41af6998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/PMS     (  902): acquireWL(4249aa08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4249aa08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
D/PowerUI ( 1118): closing low battery warning: level=100
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42663770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): releaseWL(42663770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  902): acquireWL(4261b858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1824253, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  902): Prepared write state in 28ms
,I/ProcessStatsService(  902): Prepared write state in 35ms
,I/ProcessStatsService(  902): Prepared write state in 10ms
,D/PMS     (  902): releaseWL(4261b858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(420c6f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10028}
,V/AlarmManager(  902): sending alarm PendingIntent{422d31d8: PendingIntentRecord{42480f38 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1483728, Int=0
,V/AlarmManager(  902): sending alarm PendingIntent{41d81c48: PendingIntentRecord{423bd640 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1506504, Int=0
V/AlarmManager(  902): sending alarm PendingIntent{422d41f0: PendingIntentRecord{42486f30 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821490, Int=1800000
V/AlarmManager(  902): sending alarm PendingIntent{420442e8: PendingIntentRecord{4246ad30 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452157637384, Int=900000
,D/PMS     (  902): acquireWL(4344d168): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1360 10028 null
,D/PMS     (  902): releaseWL(4344d168): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  902): acquireWL(4261f9d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,D/ConnectivityService(  902): Sampling interval elapsed, updating statistics ..
,D/PMS     (  902): acquireWL(4253d690): PARTIAL_WAKE_LOCK  NetworkStats 0x1 902 1000 null
,D/PMS     (  902): releaseWL(4261f9d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  902): Done.
,D/ConnectivityService(  902): Setting timer for 720seconds
,D/PMS     (  902): releaseWL(4253d690): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  902): releaseWL(420c6f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/PMS     (  902): acquireWL(434f8e18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
,D/GCM     ( 1360): Message class mow
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  902): handleInetConditionChange: starting a change hold
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1360/10028)
,D/PMS     (  902): acquireWL(4343fa10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,D/PMS     (  902): releaseWL(434f8e18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  902): releaseWL(4343fa10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  902): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  902): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=10 [120][12][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1135): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1135): nl80211: survey data missing!
E/wpa_supplicant( 1135): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1135): environment dirty rate=0 [0][0][0]
,D/PMS     (  902): acquireWL(4330a110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4330a110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  902): updateBatteryInfo
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): runPSCheck
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43533d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43533d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(434c9988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38f40: PendingIntentRecord{41e34a80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1884253, Int=0
,D/Process (  902): killProcessQuiet, pid=4281
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
I/ActivityManager(  902): Killing 4281:com.htc.cs.dm/u0a98 (adj 15): empty for 1808s
,D/PMS     (  902): releaseWL(434c9988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 4281
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4881): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4881): ====startRecUseTime====
D/htc.customization.log.level( 4881):  is 
W/CustomizationLogLevel( 4881): Level value is invalid, use default level 2
D/CustomizationManager( 4881):  Read ACC file spent 0.094 (s)
D/CIDMapFileReader( 4881): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4881): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4881): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4881): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4881): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4881): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4881): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4881): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4881): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4881): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4881): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4881): Parsing tag category name = system
I/CustomizationCIDLoader( 4881): Parsing tag category name = application
I/CustomizationCIDLoader( 4881): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4881): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4881): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4881): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4881): Parsing tag category name = Settings
D/CustomizationManager( 4881):  Read CID file spent 0.144 (s)
D/CustomizationManager( 4881):  All configurations done spent 0.144 (s)
W/HtcNativeFlag( 4881): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4881): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4881): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4881): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  902): deletePackageAsUser: pkg=com.test.thalitest, pid=4881, uid=2000 user=0
I/ActivityManager(  902): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  902): killProcessQuiet, pid=4452
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  902): Killing 4452:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
W/PackageSettings(  902): Skipping PackageSetting{42224808 com.example.hello/10356} due to missing metadata
I/ActivityManager(  902): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/ActivityManager(  902): Recipient 4452
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1861): Unregistering com.test.thalitest
E/acms    ( 1861): Could not unregister removed application com.test.thalitest
I/Prism.ItemManager( 1286): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/GeofencerStateMachine( 1434): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 1286): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  902): acquireWL(44098f98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
D/PMS     (  902): releaseWL(44098f98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1340): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1340): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "sms"
D/VoicemailCleanupService( 1227): Cleaning up data for package: com.test.thalitest
I/Launcher( 1286): Deferring update until onResume
D/Launcher( 1286): waitUntilResume // bindAppsRemoved
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1254 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1254 :
I/InputMethodManagerService(  902): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1340): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1270): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1254 :
D/PackageBroadcastService( 1240): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mmsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1254 :
I/ActivityManager(  902): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4895 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1254 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1254 :
E/ExternalAccountType( 1340): Unsupported attribute readOnly
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1254 :
I/MultiDex( 4895): install
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/MultiDex( 4895): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  902):   Scheme: "mmsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1254 :
I/MultiDex( 4895): loading existing secondary dex files
I/MultiDex( 4895): load found 1 secondary dex files
I/MultiDex( 4895): install done
I/ActivityManager(  902): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4910 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1254): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1240): CP2 sync disabled
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1240, uid=10028, userID:0
D/PMS     (  902): acquireWL(435107c0): PARTIAL_WAKE_LOCK  Icing 0x1 1240 10028 null
I/Icing   ( 1240): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 4895): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  902): releaseWL(435107c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4910): install
I/MultiDex( 4910): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4910): loading existing secondary dex files
I/MultiDex( 4910): load found 1 secondary dex files
I/MultiDex( 4910): install done
I/ActivityManager(  902): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4910): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  902): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1385): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  902): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1385): handle notify Blinkfeed plugin client changed
I/ActivityManager(  902): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1286): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2909): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  902): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4933 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4895): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
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
E/SQLiteDatabase( 4895): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4895): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4895): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4895): threadid=12: thread exiting with uncaught exception (group=0x41654e30)
E/AndroidRuntime( 4895): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4895): Process: com.google.android.gms.drive, PID: 4895
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
E/AndroidRuntime( 4895): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4895): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4895): 	at ctn.run(SourceFile:985)
E/ActivityManager(  902): App crashed! Process: com.google.android.gms.drive
D/Process ( 4895): killProcess, pid=4895
D/Process ( 4895): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
E/SQLiteLog( 2909): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2909): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63aece30
W/dalvikvm( 2909): threadid=14: thread exiting with uncaught exception (group=0x41654e30)
E/ActivityManager(  902): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2909): FATAL EXCEPTION: IntentService[UpdateCorporaService]
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
D/Process ( 2909): killProcess, pid=2909
D/Process ( 2909): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
I/ActivityManager(  902): Recipient 2909
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  902): Client com.google.android.googlequicksearchbox (pid 2909): Died!
I/ActivityManager(  902): Process com.google.android.googlequicksearchbox:search (pid 2909) has died.
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
D/WifiService(  902): Client connection lost with reason: 4
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
I/ActivityManager(  902): Recipient 4895
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Process com.google.android.gms.drive (pid 4895) has died.
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10975ms
W/PackageManager(  902): Unable to load service info ResolveInfo{433d8bf8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  902): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  902): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  902): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  902): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  902): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  902): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  902): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  902): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  902): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  902): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4933): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4933): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4933): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4933): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4933): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4933): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4933): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4933): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4933): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4933): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4933): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4933): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4933): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4933): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4933): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4933): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4933): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4933): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4933): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4933): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4933): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4933): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4933): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4933): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4933): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4933): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4933): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4933): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4933): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4933): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4933): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4933): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4933): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4933): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4933): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4933): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4933): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4933): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4933): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4933): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4933): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4933): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4933): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4933): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4933): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4933): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4933): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4933): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4933): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4933): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4933): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4933): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4933): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4933): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4933): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4933): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4933): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4933): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4933): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4933): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4933): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4933): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4933): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4933): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4933): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4933): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4933): threadid=11: thread exiting with uncaught exception (group=0x41654e30)
E/AndroidRuntime( 4933): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4933): Process: com.google.android.apps.docs, PID: 4933
E/AndroidRuntime( 4933): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4933): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4933): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4933): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4933): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4933): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4933): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4933): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  902): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
E/SQLiteDatabase( 4933): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4933): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4933): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4933): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4933): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4933): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4933): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4933): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4933): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4933): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4933): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4933): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4933): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4933): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4933): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4933): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4933): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4933): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4933): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4933): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4933): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4933): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4933): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4933): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4933): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4933): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4933): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4933): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4933): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4933): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4933): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4933): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4933): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4933): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4933): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4933): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4933): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4933): Opened ClientFlag.db in read-only mode
D/Process ( 4933): killProcess, pid=4933
D/Process ( 4933): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  902): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4951 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  902): Recipient 4933
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Process com.google.android.apps.docs (pid 4933) has died.
W/ContextImpl( 4951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  902): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4964 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4951): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4951): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4951): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4951): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4951): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4951): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4951): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4951): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4951): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4951): threadid=10: thread exiting with uncaught exception (group=0x41654e30)
E/AndroidRuntime( 4951): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4951): Process: com.android.keychain, PID: 4951
E/AndroidRuntime( 4951): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4951): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4951): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4951): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4951): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4951): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4951): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4951): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  902): App crashed! Process: com.android.keychain
D/ErrorReport(  902): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 1286): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1286): loadItems() com.htc.launcher.pageview.WidgetManager@41b18e10 +
I/Prism.WidgetManager( 1286): onLoadItems() +
D/AppTag  ( 4964): getInstance(Context context)
D/Process ( 4951): killProcess, pid=4951
D/Process ( 4951): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  902): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  902): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452157710172.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  902): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  902): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  902): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  902): 	... 4 more
I/ActivityManager(  902): Recipient 4951
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Process com.android.keychain (pid 4951) has died.
D/AppTag  ( 4964): getInstance(Context context)
W/ActivityManager(  902): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10213ms
D/AppTag  ( 4964): onCreate()
D/PMS     (  902): acquireWL(43423d88): PARTIAL_WAKE_LOCK  AsyncService 0x1 4168 10160 null
D/PMS     (  902): releaseWL(43423d88): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  902): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4981 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4981): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4981 dbg=false s=true
I/DeviceManagement( 4981): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4981): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]

```
