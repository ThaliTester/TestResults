#### Test 55742142a5c2fdb_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  907): acquireWL(42bdcdf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
V/AlarmManager(  907): sending alarm PendingIntent{43f7df00: PendingIntentRecord{42bcf060 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452600958084, Int=0
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4493 uid=10078 gids={50078}
V/AlarmManager(  907): sending alarm PendingIntent{42ba2b40: PendingIntentRecord{42b59338 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452600960527, Int=60000
D/PMS     (  907): releaseWL(42bdcdf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
--------- beginning of /dev/log/main
D/SMSBackup( 4493): SMSBackupAgentService started
D/SMSBackup( 4493): Checking restore status
D/SMSBackup( 4493): Restore complete
D/SMSBackup( 4493): cancelCheckAlarm
D/SMSBackup( 4493): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/Finsky  ( 4153): [434] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4153): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  907): killProcessQuiet, pid=4296
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4296:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/CustomizationManager( 4491): ====startRecUseTime====
D/htc.customization.log.level( 4491):  is 
W/CustomizationLogLevel( 4491): Level value is invalid, use default level 2
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4296
D/CustomizationManager( 4491):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 4491): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4491): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4491): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4491): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4491): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4491): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4491): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4491): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4491): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4491): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4491): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4491): Parsing tag category name = system
I/CustomizationCIDLoader( 4491): Parsing tag category name = application
I/CustomizationCIDLoader( 4491): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4491): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4491): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4491): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4491): Parsing tag category name = Settings
D/CustomizationManager( 4491):  Read CID file spent 0.104 (s)
D/CustomizationManager( 4491):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 4491): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4491): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4491): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4491): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4491
D/PMS     (  907): acquireHCC(42b9d880): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(42a69b78): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x6ff34f78 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1147377216
D/PMS     (  907): acquireWL(44195238): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@421c9250
I/SocialFeedProvider( 1275): +onPause
I/SocialFeedProvider( 1275): -onPause
E/cutils-trace( 4491): Error opening trace file: No such file or directory (2)
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4515 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
W/asset   ( 4515): Copying FileAsset 0x5c741048 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1275): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4515): Binding Chromium to main looper Looper (main, tid 1) {420cdaa0}
I/LibraryLoader( 4515): Expected native library version number "",actual native library version number ""
I/chromium( 4515): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4515): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(43787bd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4289b0b8:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4515): 1108229680: getState(). Returning 12
D/PMS     (  907): acquireWL(43b55050): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): releaseWL(43787bd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4515): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4515): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4515): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4515): Local Branch: 
I/Adreno-EGL( 4515): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4515): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4515):                  aa63bbd948f41d15fc72f585e
W/chromium( 4515): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4515): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4515): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4515): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4515): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4515): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4515): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4515): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4515): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4515): CordovaWebView is running on device made by: HTC
,W/AwContents( 4515): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1275
I/InputMethodManagerService(  907): Enable input method client, pid=4515
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +294ms
W/ResourceType( 4515): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4515): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@421154e0, mServedView=org.apache.cordova.engine.SystemWebView{420db148 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 4515): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  907): releaseWL(44195238): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4515): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4515): JniHelper::setJavaVM(0x41c8b010), pthread_self() = 1556470624
D/JX-Cordova( 4515): jxcore cordova android initializing
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4515): Grow heap (frag case) to 11.564MB for 64402-byte allocation
,I/dalvikvm-heap( 4515): Grow heap (frag case) to 11.615MB for 96598-byte allocation
,I/dalvikvm-heap( 4515): Grow heap (frag case) to 11.678MB for 144892-byte allocation
,I/dalvikvm-heap( 4515): Grow heap (frag case) to 11.793MB for 217334-byte allocation
,I/dalvikvm-heap( 4515): Grow heap (frag case) to 11.970MB for 325996-byte allocation
,I/dalvikvm-heap( 4515): Grow heap (frag case) to 12.655MB for 733480-byte allocation
,I/dalvikvm-heap( 4515): Grow heap (frag case) to 13.251MB for 1100216-byte allocation
,I/dalvikvm-heap( 4515): Grow heap (frag case) to 14.163MB for 1650320-byte allocation
,I/dalvikvm-heap( 4515): Grow heap (frag case) to 15.511MB for 2475476-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(42b9d880): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(42a69b78): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4515): Grow heap (frag case) to 17.640MB for 3713210-byte allocation
,W/jxcore-log( 4515): Initializing JXcore engine
,W/jxcore-log( 4515): JXcore engine is ready
,W/jxcore-log( 4515): Starting JXcore engine
,W/jxcore-log( 4515): Platform android
W/jxcore-log( 4515): 
,W/jxcore-log( 4515): Process ARCH arm
W/jxcore-log( 4515): 
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): releaseWL(43b55050): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42ba8c78 u0 com.htc.htclocationservice/.AutoSettingService}
,V/LightsService(  907): setLight #0: color=#3e
,V/LightsService(  907): setLight #0: color=#3b
,V/LightsService(  907): setLight #0: color=#34
,V/LightsService(  907): setLight #0: color=#2e
,V/LightsService(  907): setLight #0: color=#27
,V/LightsService(  907): setLight #0: color=#20
,V/LightsService(  907): setLight #0: color=#1a
,V/LightsService(  907): setLight #0: color=#14
,I/jxcore-log( 4515): JXcore Cordova bridge is ready!
I/jxcore-log( 4515): 
,W/jxcore-log( 4515): JXcore engine is started
,I/chromium( 4515): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 4515): Toggling radios to true
I/jxcore-log( 4515): 
,D/BluetoothAdapter( 4515): enable(): BT is already enabled..!
,D/WifiManager( 4515): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1455
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4515, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 5(ms)
D/WifiManager( 4515): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
D/WifiManager( 4515): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): TDLS: Tear down peers
I/wpa_supplicant( 1155): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4515): Radios toggled
I/jxcore-log( 4515): 
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4515): Received device characteristics:
I/jxcore-log( 4515): Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4515): Bluetooth name: HTC Desire 820
I/jxcore-log( 4515): Device name: HTC-HTC Desire 820
I/jxcore-log( 4515): 
I/jxcore-log( 4515): Perf Test app loaded loaded
I/jxcore-log( 4515): 
I/Choreographer( 4515): Skipped 94 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4515): check test folder
I/jxcore-log( 4515): 
,I/jxcore-log( 4515): found test : ./testFindPeers.js
I/jxcore-log( 4515): 
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1155): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1155): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1155): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8bbabc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1155):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1155): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1155): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 48 (NL80211_CMD_DISCONN,ECT) received for wlan0
D/wpa_supplicant( 1155): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  907): acquireWL(43b433d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
,D/WifiNative-wlan0(  907): doBoolean: RECONNECT
I/jxcore-log( 4515): found test : ./testSendData.js
I/jxcore-log( 4515): 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): Fast associate: Old scan results
I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19531 mDataStallAlarmIntent=PendingIntent{42bc5f40: PendingIntentRecord{429924e8 android broadcastIntent}}
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): Enter handleNetworkDisconnect
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
,D/WISPrService( 4138): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4138): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiService(  907): New client listening to asynchronous messages
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,V/NativeCrypto( 1360): Read error: ssl=0x65f88318: I/O error during system call, Connection timed out
D/libc    (  364): [NET] entry_id:3   entry:0xb7cdd590  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7ce1e40  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7ce1d90  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7ce1f70  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7cd8c20  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7cdd458  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7cdd2a8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WISPrService( 4138): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 4138): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(42c101c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/PMS     (  907): acquireWL(44736188): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/WifiNative-wlan0(  907): doBoolean: SCAN
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  907):    returned false
,V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x65f88318: I/O error during system call, Broken pipe
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1360/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/PMS     (  907): releaseWL(44736188): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,D/PMS     (  907): releaseWL(42c101c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
,I/chromium( 4515): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4330/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,I/NetworkMonitor( 3919): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4330/10100)
D/PMS     (  907): acquireWL(4297cf00): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3919/10154)
D/PMS     (  907): releaseWL(4297cf00): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1958/10021)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4570 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4570): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4570): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4570): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4570): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4570): Preparing secondary program dexes.
V/DexLibLoader( 4570): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4570): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4570): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4570): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4570): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4570): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4570): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4570): Dex already copied
D/OdexVerifier( 4570): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4570): Creating class loader
,V/DexLibLoader( 4570): Finished creating class loader
V/DexLibLoader( 4570): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4570): Dex already copied
D/OdexVerifier( 4570): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4570): Creating class loader
,V/DexLibLoader( 4570): Finished creating class loader
V/DexLibLoader( 4570): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4570): Dex already copied
D/OdexVerifier( 4570): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4570): Creating class loader
,V/DexLibLoader( 4570): Finished creating class loader
V/DexLibLoader( 4570): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4570): Dex already copied
D/OdexVerifier( 4570): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4570): Creating class loader
,V/DexLibLoader( 4570): Finished creating class loader
,V/DexLibLoader( 4570): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4570): DexLibLoader.ensureDexLoaded took 19 ms
,I/SensorManager(  907): mEventCount = 1200
,W/dalvikvm( 4570): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4570): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4570): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4570): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4570): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4570): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4570): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4570): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4570): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4570): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1155): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1155): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1155): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 3
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 1
I/wpa_supplicant( 1155): wpa_s->is_screen_on 1
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): selected network = 1
D/wpa_supplicant( 1155): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8bbc4e8  current_ssid=0x0
D/wpa_supplicant( 1155): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1155): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1155): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1155): check if in concurrent case
I/wpa_supplicant( 1155): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0,(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1155): RSN: PMKSA cache search - network_ctx=0xb8bbc4e8 try_opportunistic=0
D/wpa_supplicant( 1155): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1155): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1155): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1155): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1155): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1155): nl80211: Unsubscribe mgmt frames handle 0xb8bbb718 (mode change)
D/wpa_supplicant( 1155): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8bbb718
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1155):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1155):   * freq=2412
D/wpa_supplicant( 1155):   * Auth Type 0
D/wpa_supplicant( 1155):   * WPA Versions 0x2
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1155): nl80211: Connect request send successfully
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  90,7): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-48
I/wpa_supplicant( 1155): tsf=0000000102451413
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000102451429
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000102451432
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000102451424
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 102451413, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 102451429, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 102451432, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 102451424, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1155): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1155): nl80211: Connect event
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1155): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1155): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1155): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1155): TDLS: Remove peers on association
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1155): EAPOL: enable timer tick
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1155): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1155): Get randomness: len=32 entropy=5
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true,
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  907): [isWifi] getHotspotEnabled: false,
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412,
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/wpa_supplicant( 1155): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8bbb9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1155):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1155): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f2bb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1155):    broadcast key
D/WifiApDatabaseHandler(  907): updateConnectedAP...
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1155): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1155): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1155): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,E/wpa_supplicant( 1155): wlan0: Connect to SSID: NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=6
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1155): set send_ind_to_ndc = 0
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1155): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state AUTHENTICATED,
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1155): EAPOL authentication completed successfully
I/wpa_supplicant( 1155): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,W/fb4a(:<default>):StaticBindingVerifier( 4570): Verify
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false,
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 4138): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4138): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(42b66a38): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 1
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null,
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a8c390 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a8c390 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4570): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4570): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4570): Grow heap (frag case) to 9.514MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=1315
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 1315:com.htc.sense.hsp/u0a55 (adj 15): empty #17
,W/fb4a(:<default>):UserScope( 4570): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4570): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4570): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4570): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  907): Recipient 1315
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BroadcastQueue(  907): Schedule to resend BroadcastRecord{4375b898 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=907 callingUid=1000} for ResolveInfo{433dc230 com.htc.sense.hsp/.weather.location.AutoSettingReceiver m=0x108000} of com.htc.sense.hsp
,I/ActivityManager(  907): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4600 uid=10055 gids={50055, 1023, 3003, 5012}
,E/dalvikvm( 4570): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4570): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4570): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4570): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4570): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4570): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4570): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4570): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4570): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4570): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4570): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4570): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4570): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4570): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4570): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4570): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4570): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4570): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4570): Grow heap (frag case) to 9.924MB for 39954-byte allocation
,D/PluginProvider( 4600): PluginProvider onCreate
,D/PluginProvider( 4600): current plugin count: 18
,D/HtcAppUPService( 4600): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4570): Grow heap (frag case) to 10.000MB for 79892-byte allocation
,I/dalvikvm-heap( 4570): Grow heap (frag case) to 10.071MB for 84664-byte allocation
,D/AutoSetting( 4600): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/dalvikvm-heap( 4570): Grow heap (frag case) to 10.097MB for 28144-byte allocation
,D/Process (  907): killProcessQuiet, pid=4330
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4614 uid=10079 gids={50079, 3003, 5012}
I/ActivityManager(  907): Killing 4330:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4600/10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4600/10055)
D/AutoSetting( 4600): Util - no network available!
,D/AutoSetting( 4600): service - onCreate()
,D/AutoSetting( 4600): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  907): request 42649f68 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4600): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 4600): service - mHandler: cancel location update
,D/AutoSetting( 4600): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4614): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4614): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4614): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4614): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4631 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4614/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4614/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4614/10079)
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4330
,I/dalvikvm-heap( 4570): Grow heap (frag case) to 10.285MB for 75760-byte allocation
,D/Process (  907): killProcessQuiet, pid=4353
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4659 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 4353:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4474a480 u0 ReceiverList{4474a360 4570 com.facebook.katana/10027/u0 remote:42c3e650}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4474a480 u0 ReceiverList{4474a360 4570 com.facebook.katana/10027/u0 remote:42c3e650}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42d03b58 u0 ReceiverList{42d03af8 4570 com.facebook.katana/10027/u0 remote:447995e0}}
,I/ActivityManager(  907): Recipient 4353
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4659): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(42b66a38): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/ContextImpl( 4659): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
W/GAV2    ( 4659): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19533 delay=15s
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiWatchdogStateMachine(  907): WAN detection
W/ContextImpl( 4659): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/WISPrService( 4138): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4659): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  907): syncGetConfiguredNetworks
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a5bf78
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/PMS     (  907): acquireWL(432c1210): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
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
D/PMS     (  907): releaseWL(432c1210): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(44096310): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4614/10079)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  907): acquireWL(433bc0b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/wpa_supplicant( 1155): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1155): EAPOL: disable timer tick
,W/ContextImpl( 4570): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4570): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1452600924461 min interval config: 0 actual interval: 45196
D/PMS     (  907): releaseWL(44096310): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  907): acquireWL(44864e28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(433bc0b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2179): Checking schedule, now: 1452600969665 next: 1452600954429
,I/CheckinService( 2179): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2179, uid=10029, userID:0
,I/CheckinService( 2179): Preparing to send checkin request
,I/EventLogService( 2179): Accumulating logs since 1452600919569
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4659/10151)
,V/WebViewChromiumFactoryProvider( 4659): Binding Chromium to main looper Looper (main, tid 1) {420d30f0}
,I/LibraryLoader( 4659): Expected native library version number "",actual native library version number ""
,I/chromium( 4659): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4659): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(443cf9f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4659): BLUETOOTH permission is missing!
D/PMS     (  907): acquireWL(443cf950): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
D/PMS     (  907): releaseWL(443cf950): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,I/Adreno-EGL( 4659): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4659): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4659): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4659): Local Branch: 
I/Adreno-EGL( 4659): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4659): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4659):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4659): Starting up...
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4659/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4659/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1155): Change stage from stage0 to stage3
,I/wpa_supplicant( 1155): wlan0: Background scan every 600 seconds
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=4317
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
I/ActivityManager(  907): Killing 4317:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Recipient 4317
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4714 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4714): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4714): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4714): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4714): install
,I/MultiDex( 4714): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4714): loading existing secondary dex files
,I/MultiDex( 4714): load found 3 secondary dex files
,I/MultiDex( 4714): install done
,W/dalvikvm( 4714): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4714): VFY: unable to resolve instance field 36
,W/dalvikvm( 4714): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4714): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4714): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1226): callingUid 10029, callindPid: 1226
,D/LocationInitializer( 2179): Restart initialization of location
,E/MDM     ( 1226): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1360): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.
,W/dalvikvm( 4714): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4714): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
W/dalvikvm( 4714): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4714): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4714): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4714): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4714): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/ActivityManager(  907): Resuming delayed broadcast
,W/GCoreFlp( 1226): No location to return for getLastLocation()
,W/FusedLocationProvider( 1226): location=null
D/PMS     (  907): acquireWL(423c7710): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(423c7710): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4714): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3870357648
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  907): releaseWL(43b433d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3815780525
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3955/10053)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4614/10079)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3919/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 3919): type=WIFI subType= reason=null isConnected=true
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/PMS     (  907): acquireWL(43a0f3b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1958/10021)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/WVCdm   (  371): CdmEngine::CloseSession
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1345): Unsupported attribute readOnly
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 4600): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4600/10055)
D/AutoSetting( 4600): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 4600): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 4600): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 4600): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 4600): service - handleMessage() setting current location null
D/AutoSetting( 4600): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4600): service - onStartCommand() check timezone in 30000
,D/MobileConnectivityChangeReceiver( 4614): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4614): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4600/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4659/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42b89378): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): acquireWL(42be7750): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42b89378): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  907): releaseWL(43a0f3b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1452600924461 min interval config: 0 actual interval: 46171
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42be7750): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4714): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4714): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4714): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4714): Local Branch: 
I/Adreno-EGL( 4714): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4714): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4714):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4714): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4714): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4714): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4714): Local Branch: 
I/Adreno-EGL( 4714): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4714): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4714):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4714): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4714): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4714): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4714): Local Branch: 
I/Adreno-EGL( 4714): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4714): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4714):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 4515): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4515): threadid=1: thread exiting with uncaught exception (group=0x41c9ce30)
,E/ActivityManager(  907): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4515): FATAL EXCEPTION: main
E/AndroidRuntime( 4515): Process: com.test.thalitest, PID: 4515
E/AndroidRuntime( 4515): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4515): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4515): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4515): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4515): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4515): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4515): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4515): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4515): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4515): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4515): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4515): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4515): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4515): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4515): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4515): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4515): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4515): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4515): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  907):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  907): acquireWL(42c34a70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
,W/asset   (  907): Copying FileAsset 0x62d736f8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/Settings( 4714): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PMS     (  907): Going to sleep due to screen timeout...
,W/PMS     (  907): mWirelessDisplayManager is null
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@427f96c0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  907): pid=907, uid=1000
,W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@427f96c0, eanble = 0, strlen(mName) = 59
,W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4287b588
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@42a40b78
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4714/10029)
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2179): [NET] getaddrinfo-,err=8
D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2179): [NET] getaddrinfo-, 1
,D/libc    ( 2179): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2da0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 53
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2179): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2179): Sending checkin request (12133 bytes)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=6 [15][1][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-55 , oldRssi= -200
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 330ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4338f428)
D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=4515
D/PMS     (  907): acquireWL(44700bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  907): wakingUp
,I/BatteryService(  907): n_update end
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
,D/NfcService( 1256): applyRouting -2
D/PMS     (  907): releaseWL(44700bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
D/PMS     (  907): acquireWL(43c772b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  907): releaseWL(43c772b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMN     (  907): onScreenOn
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1256): applyRouting - 0
,D/MtpService( 1958): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1256): applyRouting -2
,D/MtpService( 1958): [MTP][onReceive]-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): acquireWL(43d26600): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
W/ActivityManager(  907): Activity pause timeout for ActivityRecord{44745878 u0 com.test.thalitest/.MainActivity t2 f}
,D/AutoSetting( 4600): receiver - intent: android.intent.action.USER_PRESENT
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/PMS     (  907): releaseWL(43d26600): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
,D/AutoSetting( 4600): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19534 delay=15s
D/TetherSettings( 4138): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4138): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4138): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4138): Cust_ConnectToPC   : spcsc>false
D/        ( 4138): Cust_ConnectToPC   : IPT>true
,D/        ( 4138): Cust_ConnectToPC   : Singel_USB>false
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): SET_SCREEN_ON:On
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1155): BG scan when screen On
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): Match BG scan, scan!
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  907):    returned true
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
I/ClockThread( 1116): stop update clock
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,W/Settings( 4138): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/SmartNS_Utility( 4138): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4138): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4138): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/PSReceiver( 4138): onReceive:android.intent.action.USER_PRESENT
I/FeedHostManager( 1275): [onResume]
,I/FeedProviderManager( 1275): onResume
I/SocialFeedProvider( 1275): +onResume
I/SocialFeedProvider( 1275): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1275): -onResume
D/NetworkPolicy(  907): updateScreenOn: false
W/ContextImpl( 4138): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4138): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4138): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4138):  defaultType:0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1275/10076)
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4761 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  907): releaseWL(42c34a70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/PMS     (  907): acquireWL(433853f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(433853f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  907): acquireWL(43aebc20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/PMS     (  907): releaseWL(43aebc20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1776): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): onScreenOn: 1452600972056
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1776): onScreenOn: 1452600972056
W/ContextImpl( 4761): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4287b588
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4287b588, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@42a40b78
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
,D/Process (  907): killProcessQuiet, pid=4371
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/PMS     (  907): acquireWL(446a34a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
D/PMS     (  907): acquireWL(43d267e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4761 1000 null
I/ActivityManager(  907): Killing 4371:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/FeedHostManager( 1275): [onPause]
,I/FeedProviderManager( 1275): onPause
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@421c9250
I/SocialFeedProvider( 1275): +onPause
,I/SocialFeedProvider( 1275): -onPause
,D/SmartSyncUtils( 4761): isEpsOn(), nState = 0
,W/fb4a(:<default>):UserScope( 4570): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  907): Recipient 4371
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/PMS     (  907): releaseWL(43d267e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/fb4a(:<default>):UserScope( 4570): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19534 mDataStallAlarmIntent=PendingIntent{438d6080: PendingIntentRecord{429924e8 android broadcastIntent}}
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/PMS     (  907): acquireWL(43d2eb48): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/SmartSyncUtils( 4761): getMobilePolicyEnabled, result = true
,D/Process (  907): killProcessQuiet, pid=4257
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(446a34a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/ActivityManager(  907): Killing 4257:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4257
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4570): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =276c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): SET_SCREEN_ON:Off
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1155): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  371): ParamSet string: screen_state=off
W/ContextImpl( 4761): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/SmartSyncUtils( 4761): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4761): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4761): getMobilePolicyEnabled, result = true
,D/WifiService(  907): New client listening to asynchronous messages
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a40b78
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
,W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a40b78, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a40b78, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a40b78
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42b742a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42b742a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/PMS     (  907): acquireWL(4376add0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] getTotalRam: 1873 Mb
D/PMS     (  907): releaseWL(4376add0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4429d478): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4429d478): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1776): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1776): onScreenOff
,D/AutoSetting( 4600): service - mHandler: cancel location update
,D/AutoSetting( 4600): service -           changes count: 0
D/PMS     (  907): releaseWL(443cf9f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true,
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(43d2eb48): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null,
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL,
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-94
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=11 entropy=0
D/wpa_supplicant( 1155): Add randomness: count=12 entropy=1
D/wpa_supplicant( 1155): Add randomness: count=13 entropy=2
D/wpa_supplicant( 1155): Add randomness: count=14 entropy=3
D/wpa_supplicant( 1155): Add randomness: count=15 entropy=4
D/wpa_supplicant( 1155): Add randomness: count=16 entropy=5
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:b0:03:6e type 0 added
I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f,:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-94
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=17 entropy=6
D/wpa_supplicant( 1155): Add randomness: count=18 entropy=7
D/wpa_supplicant( 1155): Add randomness: count=19 entropy=8
D/wpa_supplicant( 1155): Add randomness: count=20 entropy=9
D/wpa_supplicant( 1155): Add randomness: count=21 entropy=10
D/wpa_supplicant( 1155): Add randomness: count=22 entropy=11
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4373c868 target=com.android.internal.util.StateMachine$,SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (779) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-48
I/wpa_supplicant( 1155): tsf=0000000107973649
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000107973690
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000107973700
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000107973677
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000107973710
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-94
I/wpa_supplicant( 1155): tsf=0000000107973721
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4373c868 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4373c868 target=com.android.internal.util.StateMachine$SmHandler }
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 107973649, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 107973690, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 107973700, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 107973677, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 107973710, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  907): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -94, frequency: 2437, timestamp: 107973721, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-94], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [9][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
,I/CheckinTask( 2179): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2179): Checking schedule, now: 1452600974185 next: 1453123911180
,I/CheckinService( 2179): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,I/CheckinService( 2179): Checking schedule, now: 1452600974232 next: 1453123911180
,I/CheckinService( 2179): active receiver: disabled
,D/CheckinService( 2179): Recording last checkin time for package unspecified as 1452600974239
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(44864e28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/PMS     (  907): acquireWL(4339dc80): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1360): [NET] getaddrinfo-, 1
D/libc    ( 1360): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =17ff +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 86,
D/libc    (  364): [NET]res_nsend:resplen=79,
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 1360): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,I/GAV2    ( 4659): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(4412fe60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/PMS     (  907): releaseWL(4339dc80): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(4412fe60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42bf6af0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(42bf6af0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=20 [10][2][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=4417
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4417:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4417
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1500): service - handleMessage() stop self
,D/AutoSetting( 1500): service - onDestroy() END
,D/AutoSetting( 1500): service - handleMessage() quit looper
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4796 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/dalvikvm-heap( 1275): Grow heap (frag case) to 12.590MB for 53840-byte allocation
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1275): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Launcher( 1275): Deferring update until onResume
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,D/Launcher( 1275): waitUntilResume // bindAppsUpdated
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Scheme: "sms"
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,E/ExternalAccountType( 1345): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,W/dalvikvm( 4796): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4796): VFY: unable to resolve instance field 36
,W/dalvikvm( 4796): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,V/JNIHelp ( 4796): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel   ( 4796): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4796): MmsConfig.loadMmsSettings
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4819 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4796, uid=10111, userID:0
,W/Settings( 4796): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4796, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4796, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4796, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4796, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4796, uid=10111, userID:0
,D/MessageFrequencyProvider( 4819): onCreate
D/PMS     (  907): acquireWL(42bec9d8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4796 10111 null
,V/GetPrviateResource( 4819): GetPrviateResource
,V/GetPrviateResource( 4819): GetPrviateResource
,D/MmsCustomizationProvider( 4819): query uri: content://htc-mms-customization/mms-ua/ua_string
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 4600): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4600): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/Process (  907): killProcessQuiet, pid=3882
,I/ActivityManager(  907): Killing 3882:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/MmsCustomizationProvider( 4819): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/ProviderInstaller( 4796): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  907): acquireWL(422a5658): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 4796): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4796): MmsConfig.loadFromDatabase
D/PMS     (  907): releaseWL(42bec9d8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PMS     (  907): releaseWL(422a5658): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Babel   ( 4796): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4796): MmsConfig.loadFromResources
,E/Babel   ( 4796): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4796): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/Process (  907): killProcessQuiet, pid=4442
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Killing 4442:com.htc.calendar/u0a13 (adj 15): empty #17
,W/PackageManager(  907): Unable to load service info ResolveInfo{42c2acd0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/PMS     (  907): acquireWL(42be5ba0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Recipient 4442
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
D/MessageCustFlag( 4819): sense_version=6.0
D/BTAccessoryUtil( 4819): createReceiver
D/BTAccessoryUtil( 4819): registerReceiver return intent = null
D/MessageCustFlag( 4819): sku_id=99
W/SystemReader( 4819): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4819): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4819): networkCode: 
,D/MessageCustFlag( 4819): sku_id=99
D/MmsConfig( 4819): SIE smsPri: null
,D/MmsConfig( 4819): networkCode: 
,D/HtcTelephonyCapability( 4819): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4819): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4819): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4819): Cannot find qct_8960_interface, use default value instead
,I/ActivityManager(  907): Recipient 3882
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(42be5ba0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42bd3198): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(433be788): PARTIAL_WAKE_LOCK  AsyncService 0x1 4114 10160 null
,D/PMS     (  907): releaseWL(433be788): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/dalvikvm-heap( 4114): Grow heap (frag case) to 13.506MB for 1821008-byte allocation
D/PMS     (  907): releaseWL(42bd3198): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  907): acquireWL(42c6d9b8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4114): Grow heap (frag case) to 15.238MB for 1821008-byte allocation
,D/PMS     (  907): releaseWL(42c6d9b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42c36058): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  907): releaseWL(42c36058): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(437766e0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2179): Null package name or gms related package.  Ignoreing.
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
,I/Icing   ( 2179): updateResources: need to parse f{com.google.android.gms}
,I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(43cdddc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43cdddc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42b76560): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42b76560): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42c30540): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42c30540): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(447ab4b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(447ab4b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 583 ms] updated apps [took 583 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@42160d10 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,I/Icing   ( 2179): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2179): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(437766e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1275): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1275): onLoadItems() -
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@42160d10 -
,D/PhoneApp( 1240): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1240): -- N1 =0
,D/PhoneApp( 1240): -- N2 =0
,D/PhoneApp( 1240): -- N3 =0
,W/ActivityManager(  907): Activity destroy timeout for ActivityRecord{44745878 u0 com.test.thalitest/.MainActivity t2 f}
,D/Messaging( 4819): mNeedToUpdateDate2 start
,D/MmsConfig( 4819): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4819): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4819): 
D/MmsAsyncWorkHandler( 4819): HM tk = 20001
,D/ReportIndicatorCache( 4819): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4819): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@420d5470
,I/Messaging( 4819): mccmnc> 
D/DraftCache( 4819): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4819): [DraftCache/1] refresh
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsConfig( 4819): networkCode: 
,D/Messaging( 4819): ViewCache CreatePreloadOnlyConversationList
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/PhoneStorageUtil( 4819): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4819): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4819): createReceiver
,D/MessageCustFlag( 4819): sense_version=6.0
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Jerry   ( 4819): start to preload cursor >>>>>>>
,D/TelephUtils( 1240): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1240): Update uri=content://mms, match=0
,V/MmsProvider( 1240): selection=st=129 AND m_type!=134
,D/Messaging( 4819): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4819): TransactionService is going to be woken up.
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,V/TransactionService( 4819): 1-Creating TransactionService
,D/Messaging( 4819): mNeedToUpdateDate2: false
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/TransactionService( 4819): onStartCommand: 1
D/MmsSystemEventReceiver( 4819): unRegisterForConnectionStateChanges
V/TransactionService( 4819): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4819): Loading previous transactions.
,D/AccFlag ( 1240): sku_id=99
,D/DraftCache( 4819): [DraftCache/481] rebuildCache
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1240): device_type: 1
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1240):  phoneType = -1
D/TransactionService( 4819): Force set service start id to 1
V/TransactionService( 4819): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4819): unRegisterForConnectionStateChanges
D/TransactionService( 4819): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4819): Destroying TransactionService
,V/TransactionService( 4819): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4819): ViewCache CreatePreload
,D/Messaging( 4819): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Messaging( 4819): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/Jerry   ( 1240): URI_DRAFT
,D/Cust_MMSMS( 4819): _has_set_default_values_2=true
,D/DraftCache( 4819): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4819): [DraftCache/481] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4819): 
D/MmsAsyncWorkHandler( 4819): HM tk = 20002
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1240): sku_id=99
,D/MsgPreferenceUtils( 4819): def_index: 0
,D/MsgPreferenceUtils( 4819): globalIndex = 1
D/MsgPreferenceUtils( 4819): phone state: true
D/MsgPreferenceUtils( 4819): sd state: false
,D/MsgPreferenceUtils( 4819): vIndex = 0
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1240): sku_id=99
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{44104cc8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/Process (  907): killProcessQuiet, pid=3955
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3955:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3955
,I/GAV4    ( 4796): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-94
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=23 entropy=12
D/wpa_supplicant( 1155): Add randomness: count=24 entropy=13
D/wpa_supplicant( 1155): Add randomness: count=25 entropy=14
D/wpa_supplicant( 1155): Add randomness: count=26 entropy=15
D/wpa_supplicant( 1155): Add randomness: count=27 entropy=16
D/wpa_supplicant( 1155): Add randomness: count=28 entropy=17
D/wpa_supplicant( 1155): Add randomness: count=29 entropy=18
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -50
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 ,rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-94
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=30 entropy=19
D/wpa_supplicant( 1155): Add randomness: count=31 entropy=20
D/wpa_supplicant( 1155): Add randomness: count=32 entropy=21
D/wpa_supplicant( 1155): Add randomness: count=33 entropy=22
D/wpa_supplicant( 1155): Add randomness: count=34 entropy=23
D/wpa_supplicant( 1155): Add randomness: count=35 entropy=24
D/wpa_supplicant( 1155): Add randomness: count=36 entropy=25
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (926) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-48
I/wpa_supplicant( 1155): tsf=0000000125174458
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-50
I/wpa_supplicant( 1155): tsf=0000000125174494
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000107973700
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000125174483
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
,I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000125174524
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-94
I/wpa_supplicant( 1155): tsf=0000000125174514
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000125174533
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -50, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 125174458, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 125174494, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 107973700, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 125174483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 125174524, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -94, frequency: 2437, timestamp: 125174514, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 125174533, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 7 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-94], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == (7) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42b6cc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(42b6cc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 4600): service - mHandler: update timezone
,D/AutoSetting( 1500): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1500): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1500): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1500): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1500): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/DotMatrix( 1563): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1500): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1500): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1500): service - mHandler: update timezone
,D/AutoSetting( 1500): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1500): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1500): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1500): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{423814b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 3 7 3 11
,D/PMS     (  907): acquireWL(44200978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{429ceec8: PendingIntentRecord{42f86e00 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126022, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{429ad018: PendingIntentRecord{43271258 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136708, Int=0
,D/PMS     (  907): acquireWL(42c8f250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(448dc338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(448dc338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42c8f250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44200978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(442bf960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
,D/AutoSetting( 4600): service - handleMessage() stop self
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/PMS     (  907): releaseWL(442bf960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/AutoSetting( 4600): service - handleMessage() quit looper
,D/AutoSetting( 4600): service - onDestroy() END
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1155): Change stage from stage3 to stage0
D/PMS     (  907): acquireWL(446cd440): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): acquireWL(43905ea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(431cd2f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1226): Vacuum at: now=1452601002962 tag=VacuumService
,D/PMS     (  907): releaseWL(446cd440): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(433bf900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(433bf900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(431cd2f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43de51c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43905ea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(43de51c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4394c148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(4394c148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(439abec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(439abec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(43bdc6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42566870: PendingIntentRecord{42a60ce8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141178, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(433be078): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(43bdc6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fde9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-94
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=37 entropy=26
D/wpa_supplicant( 1155): Add randomness: count=38 entropy=27
D/wpa_supplicant( 1155): Add randomness: count=39 entropy=28
D/wpa_supplicant( 1155): Add randomness: count=40 entropy=29
D/wpa_supplicant( 1155): Add randomness: count=41 entropy=30
D/wpa_supplicant( 1155): Add randomness: count=42 entropy=31
D/wpa_supplicant( 1155): Add randomness: count=43 entropy=32
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): ,5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-94
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=44 entropy=33
D/wpa_supplicant( 1155): Add randomness: count=45 entropy=34
D/wpa_supplicant( 1155): Add randomness: count=46 entropy=35
D/wpa_supplicant( 1155): Add randomness: count=47 entropy=36
D/wpa_supplicant( 1155): Add randomness: count=48 entropy=37
D/wpa_supplicant( 1155): Add randomness: count=49 entropy=38
D/wpa_supplicant( 1155): Add randomness: count=50 entropy=39
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (926) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-48
I/wpa_supplicant( 1155): tsf=0000000142354835
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000142354871
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000142354881
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000125174483
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000142354902
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-94
I/wpa_supplicant( 1155): tsf=0000000142354891
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS],
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000142354912
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 142354835, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 142354871, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 142354881, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 125174483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 142354902, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -94, frequency: 2437, timestamp: 142354891, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 142354912, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 7 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  69, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-94], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  907): killProcessQuiet, pid=4456
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4456:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4456
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
D/PMS     (  907): releaseWL(433be078): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42b561f8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(43937508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=154008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43937508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=51 entropy=40
D/wpa_supplicant( 1155): Add randomness: count=52 entropy=41
D/wpa_supplicant( 1155): Add randomness: count=53 entropy=42
D/wpa_supplicant( 1155): Add randomness: count=54 entropy=43
D/wpa_supplicant( 1155): Add randomness: count=55 entropy=44
D/wpa_supplicant( 1155): Add randomness: count=56 entropy=45
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable netwo,rk found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): Add randomness: count=57 entropy=46
D/wpa_supplicant( 1155): Add randomness: count=58 entropy=47
D/wpa_supplicant( 1155): Add randomness: count=59 entropy=48
D/wpa_supplicant( 1155): Add randomness: count=60 entropy=49
D/wpa_supplicant( 1155): Add randomness: count=61 entropy=50
D/wpa_supplicant( 1155): Add randomness: count=62 entropy=51
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (926) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000159805035
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000159805072
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000159805084
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
,I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000125174483
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000159805094
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-94
I/wpa_supplicant( 1155): tsf=0000000142354891
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
,I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000159805104
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 159805035, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 159805072, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 159805084, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 125174483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 159805094, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -94, frequency: 2437, timestamp: 142354891, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 159805104, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 7 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-94], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (7) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/AutoSetting( 1500): service - handleMessage() stop self
,D/AutoSetting( 1500): service - onDestroy() END
,D/AutoSetting( 1500): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4082
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4082:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4082
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(43866540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(43866540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=63 entropy=52
D/wpa_supplicant( 1155): Add randomness: count=64 entropy=53
D/wpa_supplicant( 1155): Add randomness: count=65 entropy=54
D/wpa_supplicant( 1155): Add randomness: count=66 entropy=55
D/wpa_supplicant( 1155): Add randomness: count=67 entropy=56
D/wpa_supplicant( 1155): Add randomness: count=68 entropy=57
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable netwo,rk found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=69 entropy=58
D/wpa_supplicant( 1155): Add randomness: count=70 entropy=59
D/wpa_supplicant( 1155): Add randomness: count=71 entropy=60
D/wpa_supplicant( 1155): Add randomness: count=72 entropy=61
D/wpa_supplicant( 1155): Add randomness: count=73 entropy=62
D/wpa_supplicant( 1155): Add randomness: count=74 entropy=63
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement ,id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (779) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000177225116
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000177225154
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000177225164
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000125174483
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000177225174
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000177225184
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 177225116, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 177225154, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 177225164, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 125174483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 177225174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 177225184, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/TelephonyReceiver( 1240): switchBindHtcMsgCursor: null,
,D/PMS     (  907): acquireWL(44214910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{446e8d08: PendingIntentRecord{42f86e00 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186044, Int=0
D/PMS     (  907): releaseWL(44214910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(441509e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL,
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=8 [35][3][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42ee5478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(441509e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42ee5478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(440fef20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(440fef20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43907b48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1155): Change stage from stage0 to stage3
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(4339e7a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43c51180): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43907b48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PerfProfileCollectorService( 2179): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 2179): removeStateFiles() called
,D/PerfProfileCollectorService( 2179): User is not opt-in to Usage & Diagnostics.
D/PMS     (  907): releaseWL(43c51180): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43c92860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(43c92860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(431c8930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(431c8930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1226): Scheduling Phenotype for one-off execution 5921 seconds from now (1452601052609)
,D/GetConfigurationSnapshotOperation( 1226): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1226): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1226): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b162 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 159
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [11][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4339e7a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(442413c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(442413c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4423d8a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(4423d8a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(441fe9e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(441fe9e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=75 entropy=64
D/wpa_supplicant( 1155): Add randomness: count=76 entropy=65
D/wpa_supplicant( 1155): Add randomness: count=77 entropy=66
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=78 entropy=67
D/wpa_supplicant( 1155,): Add randomness: count=79 entropy=68
D/wpa_supplicant( 1155): Add randomness: count=80 entropy=69
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (779) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000194423887
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000194423928
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000194423951
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000125174483
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000177225174
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000177225184
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 194423887, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 194423928, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 194423951, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 125174483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 177225174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 177225184, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/ClearcutLoggerApiImpl( 1360): disconnect managed GoogleApiClient
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=81 entropy=70
D/wpa_supplicant( 1155): Add randomness: count=82 entropy=71
D/wpa_supplicant( 1155): Add randomness: count=83 entropy=72
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=84 entropy=73
D/wpa_supplicant( 1155,): Add randomness: count=85 entropy=74
D/wpa_supplicant( 1155): Add randomness: count=86 entropy=75
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000211850600
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000211850626
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000211850637
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 211850600, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 211850626, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 211850637, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42a071d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=214008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42a071d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425e1db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{428fddb8: PendingIntentRecord{43f7d748 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=223443, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4902 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{42a2c308: PendingIntentRecord{42b61bd8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452601076577, Int=10800000
,D/PMS     (  907): releaseWL(425e1db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4902/10049)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,D/Process (  907): killProcessQuiet, pid=4493
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
I/ActivityManager(  907): Killing 4493:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4493
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42957da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/PMS     (  907): releaseWL(42957da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42c6c8b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{4339e730: PendingIntentRecord{43f7d748 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226100, Int=0
,D/PMS     (  907): releaseWL(42c6c8b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=87 entropy=76
D/wpa_supplicant( 1155): Add randomness: count=88 entropy=77
D/wpa_supplicant( 1155): Add randomness: count=89 entropy=78
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=90 entropy=79
D/wpa_supplicant( 1155,): Add randomness: count=91 entropy=80
D/wpa_supplicant( 1155): Add randomness: count=92 entropy=81
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000229336036
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000229336075
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000229336095
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 229336036, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 229336075, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 229336095, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
,I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=93 entropy=82
D/wpa_supplicant( 1155): Add randomness: count=94 entropy=83
D/wpa_supplicant( 1155): Add randomness: count=95 entropy=84
D/wpa_supplicant( 1155): Add randomness: count=96 entropy=85
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=97 entropy=86
D/wpa_supplicant( 1155): Add randomness: count=98 entropy=87
D/wpa_supplicant( 1155): Add randomness: count=99 entropy=88
D/wpa_supplicant( 1155): Add randomness: count=100 entropy=89
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (519) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000246845879
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000246845919
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000246845940
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000246845959
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 246845879, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 246845919, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 246845940, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 246845959, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (4) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4298c968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(4298c968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=101 entropy=90
D/wpa_supplicant( 1155): Add randomness: count=102 entropy=91
D/wpa_supplicant( 1155): Add randomness: count=103 entropy=92
D/wpa_supplicant( 1155): Add randomness: count=104 entropy=93
D/wpa_supplicant( 1155): Add randomness: count=105 entropy=94
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80,211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=106 entropy=95
D/wpa_supplicant( 1155): Add randomness: count=107 entropy=96
D/wpa_supplicant( 1155): Add randomness: count=108 entropy=97
D/wpa_supplicant( 1155): Add randomness: count=109 entropy=98
D/wpa_supplicant( 1155): Add randomness: count=110 entropy=99
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (666) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000264355401
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000264355428
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000264355439
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000264355461
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000264355448
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 264355401, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 264355428, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 264355439, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 264355461, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 264355448, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4423cf50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=274008, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4423cf50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=111 entropy=100
D/wpa_supplicant( 1155): Add randomness: count=112 entropy=101
D/wpa_supplicant( 1155): Add randomness: count=113 entropy=102
D/wpa_supplicant( 1155): Add randomness: count=114 entropy=103
D/wpa_supplicant( 1155): Add randomness: count=115 entropy=104
D/wpa_supplicant( 1155): Add randomness: count=116 entropy=105
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=117 entropy=106
D/wpa_supplicant( 1155): Add randomness: count=118 entropy=107
D/wpa_supplicant( 1155): Add randomness: count=119 entropy=108
D/wpa_supplicant( 1155): Add randomness: count=120 entropy=109
D/wpa_supplicant( 1155): Add randomness: count=121 entropy=110
D/wpa_supplicant( 1155): Add randomness: count=122 entropy=111
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ,ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (779) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000281554786
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000281554849
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000281554868
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000281554905
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000281554886
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000281554826
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 281554786, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 281554849, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 281554868, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 281554905, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 281554886, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 281554826, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43aab2a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43aab2a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=123 entropy=112
D/wpa_supplicant( 1155): Add randomness: count=124 entropy=113
D/wpa_supplicant( 1155): Add randomness: count=125 entropy=114
D/wpa_supplicant( 1155): Add randomness: count=126 entropy=115
D/wpa_supplicant( 1155): Add randomness: count=127 entropy=116
D/wpa_supplicant( 1155): Add randomness: count=128 entropy=117
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters,
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
,I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=129 entropy=118
,D/wpa_supplicant( 1155): Add randomness: count=130 entropy=119
D/wpa_supplicant( 1155): Add randomness: count=131 entropy=120
D/wpa_supplicant( 1155): Add randomness: count=132 entropy=121
D/wpa_supplicant( 1155): Add randomness: count=133 entropy=122
D/wpa_supplicant( 1155): Add randomness: count=134 entropy=123
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (779) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000298995675
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000298995717
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000298995729
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000298995754
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000298995742
,I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000298995705
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 298995675, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 298995717, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 298995729, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 298995754, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 298995742, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 298995705, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43fb2c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43fb2c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=135 entropy=124
D/wpa_supplicant( 1155): Add randomness: count=136 entropy=125
D/wpa_supplicant( 1155): Add randomness: count=137 entropy=126
D/wpa_supplicant( 1155): Add randomness: count=138 entropy=127
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=139 entropy=128
D/wpa_supplicant( 1155): Add randomness: count=140 entropy=129
D/wpa_supplicant( 1155): Add randomness: count=141 entropy=130
D/wpa_supplicant( 1155): Add randomness: count=142 entropy=131
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (779) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000316385043
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000316385081
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000316385091
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000298995754
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000298995742
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000316385071
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 316385043, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 316385081, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 316385091, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 298995754, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 298995742, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 316385071, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults,
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=143 entropy=132
D/wpa_supplicant( 1155): Add randomness: count=144 entropy=133
D/wpa_supplicant( 1155): Add randomness: count=145 entropy=134
D/wpa_supplicant( 1155): Add randomness: count=146 entropy=135
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=147 entropy=136
D/wpa_supplicant( 1155): Add randomness: count=148 entropy=137
D/wpa_supplicant( 1155): Add randomness: count=149 entropy=138
D/wpa_supplicant( 1155): Add randomness: count=150 entropy=139
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000333809230
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000333809266
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000333809276
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000333809256
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): De,faultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 333809230, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 333809266, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 333809276, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 333809256, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43951a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=334008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43951a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42b6ce70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42b6ce70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=151 entropy=140
D/wpa_supplicant( 1155): Add randomness: count=152 entropy=141
D/wpa_supplicant( 1155): Add randomness: count=153 entropy=142
D/wpa_supplicant( 1155): Add randomness: count=154 entropy=143
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=155 entropy=144
D/wpa_supplicant( 1155): Add randomness: count=156 entropy=145
D/wpa_supplicant( 1155): Add randomness: count=157 entropy=146
D/wpa_supplicant( 1155): Add randomness: count=158 entropy=147
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000351194998
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000351195034
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000351195044
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000351195024
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 351194998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 351195034, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 351195044, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 351195024, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=159 entropy=148
D/wpa_supplicant( 1155): Add randomness: count=160 entropy=149
D/wpa_supplicant( 1155): Add randomness: count=161 entropy=150
D/wpa_supplicant( 1155): Add randomness: count=162 entropy=151
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=163 entropy=152
D/wpa_supplicant( 1155): Add randomness: count=164 entropy=153
D/wpa_supplicant( 1155): Add randomness: count=165 entropy=154
D/wpa_supplicant( 1155): Add randomness: count=166 entropy=155
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000368554683
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1,
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000368554720
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000368554730
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000368554710
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 368554683, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 368554720, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 368554730, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 368554710, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/PMS     (  907): acquireWL(44146b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44146b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=167 entropy=156
D/wpa_supplicant( 1155): Add randomness: count=168 entropy=157
D/wpa_supplicant( 1155): Add randomness: count=169 entropy=158
D/wpa_supplicant( 1155): Add randomness: count=170 entropy=159
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=171 entropy=160
D/wpa_supplicant( 1155): Add randomness: count=172 entropy=161
D/wpa_supplicant( 1155): Add randomness: count=173 entropy=162
D/wpa_supplicant( 1155): Add randomness: count=174 entropy=163
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
,I/wpa_supplicant( 1155): tsf=0000000385997713
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000385997749
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000385997759
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48,
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000385997738
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 385997713, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 385997749, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 385997759, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 385997738, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults,
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == (4) end of scan result ==
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42bd8020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=394008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42bd8020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=175 entropy=164
D/wpa_supplicant( 1155): Add randomness: count=176 entropy=165
D/wpa_supplicant( 1155): Add randomness: count=177 entropy=166
D/wpa_supplicant( 1155): Add randomness: count=178 entropy=167
D/wpa_supplicant( 1155): Add randomness: count=179 entropy=168
D/wpa_supplicant( 1155): Add randomness: count=180 entropy=169
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No su,itable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=181 entropy=170
D/wpa_supplicant( 1155): Add randomness: count=182 entropy=171
D/wpa_supplicant( 1155): Add randomness: count=183 entropy=172
D/wpa_supplicant( 1155): Add randomness: count=184 entropy=173
D/wpa_supplicant( 1155): Add randomness: count=185 entropy=174
D/wpa_supplicant( 1155): Add randomness: count=186 entropy=175
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (781) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000403515252
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000403515290
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000403515299
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000403515279
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000403515309
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=11
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-93
I/wpa_supplicant( 1155): tsf=0000000403515319
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 403515252, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 403515290, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 403515299, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 403515279, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 403515309, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 403515319, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/Process ( 4515): killProcess, pid=4515
,D/Process ( 4515): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  907): Disable input method client, pid=4515
,I/ActivityManager(  907): Recipient 4515
I/WindowState(  907): WIN DEATH: Window{4382eaf8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  907): Process com.test.thalitest (pid 4515) has died.
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/PMS     (  907): acquireWL(42c860a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{447beee0: PendingIntentRecord{441068c0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=405745, Int=300000
,D/PMS     (  907): releaseWL(42c860a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  907): acquireWL(43a8a690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43a8a690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=187 entropy=176
D/wpa_supplicant( 1155): Add randomness: count=188 entropy=177
D/wpa_supplicant( 1155): Add randomness: count=189 entropy=178
D/wpa_supplicant( 1155): Add randomness: count=190 entropy=179
D/wpa_supplicant( 1155): Add randomness: count=191 entropy=180
D/wpa_supplicant( 1155): Add randomness: count=192 entropy=181
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No su,itable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): Add randomness: count=193 entropy=182
D/wpa_supplicant( 1155): Add randomness: count=194 entropy=183
D/wpa_supplicant( 1155): Add randomness: count=195 entropy=184
,D/wpa_supplicant( 1155): Add randomness: count=196 entropy=185
D/wpa_supplicant( 1155): Add randomness: count=197 entropy=186
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1155): Add randomness: count=198 entropy=187
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (781) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000420935248
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000420935284
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000420935294
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000420935274
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000420935304
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=11
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-93
I/wpa_supplicant( 1155): tsf=0000000420935313
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 420935248, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 420935284, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 420935294, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 420935274, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 420935304, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 420935313, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(440e6db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440e6db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-,
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
,D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1),
,I/HtcPowerSaver(  907): << updateStatus,
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=199 entropy=188
D/wpa_supplicant( 1155): Add randomness: count=200 entropy=189
D/wpa_supplicant( 1155): Add randomness: count=201 entropy=190
D/wpa_supplicant( 1155): Add randomness: count=202 entropy=191
D/wpa_supplicant( 1155): Add randomness: count=203 entropy=192
D/wpa_supplicant( 1155): Add randomness: count=204 entropy=193
D/wpa_supplicant( 1155): Add randomness: count=205 entropy=194
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_suppl,icant( 1155): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=206 entropy=195
D/wpa_supplicant( 1155): Add randomness: count=207 entropy=196
D/wpa_supplicant( 1155): Add randomness: count=208 entropy=197
D/wpa_supplicant( 1155): Add randomness: count=209 entropy=198
D/wpa_supplicant( 1155): Add randomness: count=210 entropy=199
D/wpa_supplicant( 1155): Add randomness: count=211 entropy=200
D/wpa_supplicant( 1155): Add randomness: count=212 entropy=201
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (929) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000438445498
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000438445534
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000438445544
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000438445523
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000438445553
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=11
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-93
I/wpa_supplicant( 1155): tsf=0000000438445563
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=12
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000438445574
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 438445498, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 438445534, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 438445544, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 438445523, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 438445553, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 438445563, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 438445574, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 7 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  907): acquireWL(43937878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=454008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43937878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=213 entropy=202
D/wpa_supplicant( 1155): Add randomness: count=214 entropy=203
D/wpa_supplicant( 1155): Add randomness: count=215 entropy=204
D/wpa_supplicant( 1155): Add randomness: count=216 entropy=205
D/wpa_supplicant( 1155): Add randomness: count=217 entropy=206
D/wpa_supplicant( 1155): Add randomness: count=218 entropy=207
D/wpa_supplicant( 1155): Add randomness: count=219 entropy=208
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_suppl,icant( 1155): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=220 entropy=209
D/wpa_supplicant( 1155): Add randomness: count=221 entropy=210
D/wpa_supplicant( 1155): Add randomness: count=222 entropy=211
D/wpa_supplicant( 1155): Add randomness: count=223 entropy=212
D/wpa_supplicant( 1155): Add randomness: count=224 entropy=213
D/wpa_supplicant( 1155): Add randomness: count=225 entropy=214
D/wpa_supplicant( 1155): Add randomness: count=226 entropy=215
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (929) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000455947754
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000455947791
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000438445544
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000455947781
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000455947810
,I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=11
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-93
I/wpa_supplicant( 1155): tsf=0000000455947820
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=12
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000455947830
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 455947754, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 455947791, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 438445544, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 455947781, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 455947810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 455947820, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 455947830, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 7 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (7) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44631640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44631640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=227 entropy=216
D/wpa_supplicant( 1155): Add randomness: count=228 entropy=217
D/wpa_supplicant( 1155): Add randomness: count=229 entropy=218
D/wpa_supplicant( 1155): Add randomness: count=230 entropy=219
D/wpa_supplicant( 1155): Add randomness: count=231 entropy=220
D/wpa_supplicant( 1155): Add randomness: count=232 entropy=221
D/wpa_supplicant( 1155): Add randomness: count=233 entropy=222
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DON,GLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=234 entropy=223
D/wpa_supplicant( 1155): Add randomness: count=235 entropy=224
D/wpa_supplicant( 1155): Add randomness: count=236 entropy=225
D/wpa_supplicant( 1155): Add randomness: count=237 entropy=226
D/wpa_supplicant( 1155): Add randomness: count=238 entropy=227
D/wpa_supplicant( 1155): Add randomness: count=239 entropy=228
D/wpa_supplicant( 1155): Add randomness: count=240 entropy=229
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (929) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000473396863
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000473396922
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000473396941
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000473396902
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000473396960
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=11
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-93
I/wpa_supplicant( 1155): tsf=0000000473396979
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=12
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000473396998
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 473396863, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 473396922, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 473396941, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 473396902, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 473396960, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 473396979, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 473396998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 7 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (7) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=241 entropy=230
D/wpa_supplicant( 1155): Add randomness: count=242 entropy=231
D/wpa_supplicant( 1155): Add randomness: count=243 entropy=232
D/wpa_supplicant( 1155): Add randomness: count=244 entropy=233
D/wpa_supplicant( 1155): Add randomness: count=245 entropy=234
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 11,55): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=246 entropy=235
D/wpa_supplicant( 1155): Add randomness: count=247 entropy=236
D/wpa_supplicant( 1155): Add randomness: count=248 entropy=237
D/wpa_supplicant( 1155): Add randomness: count=249 entropy=238
D/wpa_supplicant( 1155): Add randomness: count=250 entropy=239
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (929) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000490885036
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000490885073
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000490885082
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000490885062
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000490885092
,I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=11
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-93
I/wpa_supplicant( 1155): tsf=0000000473396979
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=12
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000473396998
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 490885036, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 490885073, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 490885082, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 490885062, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 490885092, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 473396979, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 473396998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 7 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (7) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43c58528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43c58528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=251 entropy=240
D/wpa_supplicant( 1155): Add randomness: count=252 entropy=241
D/wpa_supplicant( 1155): Add randomness: count=253 entropy=242
D/wpa_supplicant( 1155): Add randomness: count=254 entropy=243
D/wpa_supplicant( 1155): Add randomness: count=255 entropy=244
D/wpa_supplicant( 1155): Add randomness: count=256 entropy=245
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No su,itable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=257 entropy=246
D/wpa_supplicant( 1155): Add randomness: count=258 entropy=247
D/wpa_supplicant( 1155): Add randomness: count=259 entropy=248
D/wpa_supplicant( 1155): Add randomness: count=260 entropy=249
D/wpa_supplicant( 1155): Add randomness: count=261 entropy=250
D/wpa_supplicant( 1155): Add randomness: count=262 entropy=251
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (781) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000508153216
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000508153254
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000508153264
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000508153241
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000508153273
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=12
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000508153283
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 508153216, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 508153254, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 508153264, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 508153241, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 508153273, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 508153283, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43d63320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=514008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43d63320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=263 entropy=252
D/wpa_supplicant( 1155): Add randomness: count=264 entropy=253
D/wpa_supplicant( 1155): Add randomness: count=265 entropy=254
D/wpa_supplicant( 1155): Add randomness: count=266 entropy=255
D/wpa_supplicant( 1155): Add randomness: count=267 entropy=256
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155):, nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=268 entropy=257
D/wpa_supplicant( 1155): Add randomness: count=269 entropy=258
D/wpa_supplicant( 1155): Add randomness: count=270 entropy=259
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): Add randomness: count=271 entropy=260
D/wpa_supplicant( 1155): Add randomness: count=272 entropy=261
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (781) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000525545143
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000525545172
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_,supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000525545183
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000508153241
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000525545192
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=12
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000525545202
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 525545143, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 525545172, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 525545183, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 508153241, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 525545192, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 525545202, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43809168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43809168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=273 entropy=262
D/wpa_supplicant( 1155): Add randomness: count=274 entropy=263
D/wpa_supplicant( 1155): Add randomness: count=275 entropy=264
D/wpa_supplicant( 1155): Add randomness: count=276 entropy=265
D/wpa_supplicant( 1155): Add randomness: count=277 entropy=266
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155):, nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=278 entropy=267
D/wpa_supplicant( 1155): Add randomness: count=279 entropy=268
D/wpa_supplicant( 1155): Add randomness: count=280 entropy=269
D/wpa_supplicant( 1155): Add randomness: count=281 entropy=270
D/wpa_supplicant( 1155): Add randomness: count=282 entropy=271
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (668) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000543055250
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====,
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000543055276
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000543055287
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000543055297
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=12
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000525545202
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 543055250, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 543055276, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 543055287, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 543055297, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 525545202, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43d8ca90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43d8ca90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1155): nl80211: Disconnect event
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1155): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
I/wpa_supplicant( 1155): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1155): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8bbabc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1155):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1155): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString, CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): Wireless event: cmd=0x8b15 len=20
D/WifiNative-wlan0(  907):    returned true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiPerfLock(  907): release()
,D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19535 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WISPrService( 4138): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  907): acquireWL(43d9e3f8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/WISPrService( 4138): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1155): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,V/NativeCrypto( 1360): Read error: ssl=0x65fca690: I/O error during system call, Connection timed out
,V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x65fca690: I/O error during system call, Broken pipe
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(446c5a50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  364): [NET] entry_id:3   entry:0xb7cdd310  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7cdd850  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7cdd428  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7cdd0e8  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7cdceb0  removed 
D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 4138): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4138): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(4410e790): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4614/10079)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1360/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
I//system/bin/ip(  364): RTNETLINK answers: No such process
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): CTRL_IFACE SET 'pno'='0'
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1155): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  907):    returned true,
D/PMS     (  907): releaseWL(446c5a50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,D/PMS     (  907): releaseWL(4410e790): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  907): NoActiveNetworkState
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  907): acquireWL(443cf950): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(443cf950): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
I/NetworkMonitor( 3919): type=WIFI subType= reason=null isConnected=false
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4614/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3919/10154)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771,
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1958/10021)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/AutoSetting( 4600): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4614): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4614): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4600/10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4600/10055)
,D/AutoSetting( 4600): Util - no network available!
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4659/10151)
,D/AutoSetting( 4600): service - onCreate()
,D/AutoSetting( 4600): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 4600): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  907): request 42649f68 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4600): service - mHandler: cancel location update
,D/AutoSetting( 4600): service -           changes count: 0
,I/dalvikvm-heap( 4114): Grow heap (frag case) to 16.942MB for 1821008-byte allocation
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,I/iu.Environment( 2179): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2179): num queued entries: 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
I/iu.UploadsManager( 2179): num updated entries: 0
,I/iu.SyncManager( 2179): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=283 entropy=272
D/wpa_supplicant( 1155): Add randomness: count=284 entropy=273
D/wpa_supplicant( 1155): Add randomness: count=285 entropy=274
D/wpa_supplicant( 1155): Add randomness: count=286 entropy=275
D/wpa_supplicant( 1155): Add randomness: count=287 entropy=276
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1155):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): No APs found - clear blacklist and try again
E/wpa_supplicant( 1155): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1155): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1155): Start print parameters,
I/wpa_supplicant( 1155): wpa_s->wpa_state is 3
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): selected network = 1
D/wpa_supplicant( 1155): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8bbc4e8  current_ssid=0x0
D/wpa_supplicant( 1155): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1155): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1155): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1155): check if in concurrent case
I/wpa_supplicant( 1155): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1155): RSN: PMKSA cache search - network_ctx=0xb8bbc4e8 try_opportunistic=0
D/wpa_supplicant( 1155): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1155): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1155): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1155): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1155): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1155): nl80211: Unsubscribe mgmt frames handle 0xb8bbb718 (mode change)
D/wpa_supplicant( 1155): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8bbb718
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb8bbb718
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1155):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1155):   * freq=2412
D/wpa_supplicant( 1155):   * Auth Type 0
D/wpa_supplicant( 1155):   * WPA Versions 0x2
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1155): nl80211: Connect request send successfully
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): CTRL_IFACE SET 'pno'='1'
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1155): send_and_recv error -16 - cmd 75
,D/wpa_supplicant( 1155): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  907):    returned false
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  907): getDiscoveryDongleList
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (668) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000557801835
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000000557801858
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000557801870
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
,I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000557801880
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=12
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000525545202
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC5999698
I/wpa_supplicant( 1155): ####
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 557801835, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 557801858, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 557801870, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 557801880, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 525545202, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiStateMachine(  907): add 5 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1155): nl80211: Connect event
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz,
,D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1155): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 1155): Add randomness: count=288 entropy=277
I/wpa_supplicant( 1155): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1155): TDLS: Remove peers on association
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state CONNECTING
,D/wpa_supplicant( 1155): EAPOL: enable timer tick
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
,I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1155): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1155): Get randomness: len=32 entropy=278
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1155): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8bbb9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1155):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 11
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 10
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=1
,I/wpa_supplicant( 1155): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f2bb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1155):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1155): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1155): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1155): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1155): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1155): set send_ind_to_ndc = 0
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1155): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1155): EAPOL authentication completed successfully
I/wpa_supplicant( 1155): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..,
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T],
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WISPrService( 4138): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4138): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  907):    returned true
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 1
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1155): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(42b3d0c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a8c390 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a8c390 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1155): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1155): EAPOL: disable timer tick
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  907): releaseWL(42b3d0c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true,
D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952,
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1155): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  907): WAN detection
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4138): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  907): default: setTeardownRequested(true)
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a5bf78
,D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(429a9b88): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4614/10079)
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  907): acquireWL(43dd3c00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1452600974239 min interval config: 0 actual interval: 451702
D/PMS     (  907): acquireWL(4321ee20): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43dd3c00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2179): Checking schedule, now: 1452601425947 next: 1452601004180
,I/CheckinService( 2179): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2179, uid=10029, userID:0
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/CheckinService( 2179): Preparing to send checkin request
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
I/EventLogService( 2179): Accumulating logs since 1452600969691
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(429a9b88): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1155): Change stage from stage0 to stage3
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1340722844
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2445557968
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4714): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4714): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4714): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4714): Local Branch: 
I/Adreno-EGL( 4714): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4714): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4714):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4714): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4714): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4714): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4714): Local Branch: 
I/Adreno-EGL( 4714): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4714): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4714):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4714): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4714): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4714): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4714): Local Branch: 
I/Adreno-EGL( 4714): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4714): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4714):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  907): releaseWL(43d9e3f8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/PMS     (  907): acquireWL(43966f38): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/PMS     (  907): releaseWL(43966f38): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,I/NetworkMonitor( 3919): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4614/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3919/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
V/Tethering(  907): bSetPropertyMultiRAB:false
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
D/PMS     (  907): acquireWL(4333c548): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1958/10021)
D/PMS     (  907): releaseWL(4333c548): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,W/Settings( 4714): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4570/10027)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 4600): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4614): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 4600): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 4600): service - onStartCommand() screen is off, don't request location
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 4600): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4600): service - onStartCommand() check timezone in 30000
,D/MobileConnectivityChangeReceiver( 4614): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4600/10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4600/10055)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4659/10151)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1452600974239 min interval config: 0 actual interval: 452809
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(43d05f50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43d05f50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
I/iu.Environment( 2179): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2179): num queued entries: 0
I/iu.UploadsManager( 2179): num updated entries: 0
,I/iu.SyncManager( 2179): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1360): [NET] getaddrinfo-, 1
,D/libc    ( 1360): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =43a2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4714/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/PMS     (  907): acquireWL(42b43830): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2179): [NET] getaddrinfo-,err=8
D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2179): [NET] getaddrinfo-, 1
,D/libc    ( 2179): [NET] getaddrinfo_proxy+
V/NativeCrypto( 2179): SSL shutdown failed: ssl=0x66957458: I/O error during system call, Connection timed out
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
V/NativeCrypto( 2179): SSL shutdown failed: ssl=0x66d63a08: I/O error during system call, Connection timed out
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =aa4d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1360): [NET] getaddrinfo_proxy-, success
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2179): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2179): Sending checkin request (12252 bytes)
,D/PMS     (  907): acquireWL(43d23de8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/PMS     (  907): releaseWL(42b43830): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(43d23de8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(44112060): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(44112060): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=12 [32][4][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=100 [1][1][0]
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
,I/CheckinTask( 2179): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2179): Checking schedule, now: 1452601428074 next: 1453124365055
,I/CheckinService( 2179): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,I/CheckinService( 2179): Checking schedule, now: 1452601428106 next: 1453124365055
,I/CheckinService( 2179): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,D/CheckinService( 2179): Recording last checkin time for package unspecified as 1452601428113
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(4321ee20): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =759a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): acquireWL(4411f2c0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4796 10111 null
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1275): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 4600): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4600): handle notify Blinkfeed plugin client changed
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Launcher( 1275): Deferring update until onResume
,D/Launcher( 1275): waitUntilResume // bindAppsUpdated
,I/ActivityManager(  907): Resuming delayed broadcast
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PMS     (  907): releaseWL(4411f2c0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/ActivityManager(  907): Resuming delayed broadcast
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
D/PMS     (  907): acquireWL(44734a70): PARTIAL_WAKE_LOCK  AsyncService 0x1 4114 10160 null
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,E/ExternalAccountType( 1345): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
D/PMS     (  907): releaseWL(44734a70): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PMS     (  907): acquireWL(4414ac38): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  907): releaseWL(4414ac38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  907): acquireWL(43724bb8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43724bb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(43cf7d50): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  907): releaseWL(43cf7d50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42c8f010): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  907): releaseWL(42c8f010): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42fefc90): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2179): Null package name or gms related package.  Ignoreing.
,W/PackageManager(  907): Unable to load service info ResolveInfo{440d4a58 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Icing   ( 2179): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 570 ms] updated apps [took 570 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(42d03118): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42d03118): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/PMS     (  907): acquireWL(42c5dea8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42c5dea8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43a87530): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43a87530): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@42160d10 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,I/Icing   ( 2179): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{44784730 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/Icing   ( 2179): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(42fefc90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1275): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1275): onLoadItems() -
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@42160d10 -
,D/PhoneApp( 1240): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1240): -- N1 =0
,D/PhoneApp( 1240): -- N2 =0
,D/PhoneApp( 1240): -- N3 =0
,D/PMS     (  907): acquireWL(43a460a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=574008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43a460a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(446c8a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/BatteryService(  907): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(446c8a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 4600): service - mHandler: update timezone
,D/AutoSetting( 4600): service - handleMessage() stop self
,D/AutoSetting( 4600): service - onDestroy() END
,D/AutoSetting( 4600): service - handleMessage() quit looper
,D/AutoSetting( 1500): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1500): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1500): service - onCreate()
D/AutoSetting( 1500): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1500): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1563): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1500): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1500): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1500): service - mHandler: update timezone
,D/AutoSetting( 1500): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1500): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1500): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1500): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{4212bfb8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 1 7 2 11
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43700eb0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(442d91f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(442d91f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/AutoSetting( 1500): service - handleMessage() stop self
,D/AutoSetting( 1500): service - onDestroy() END
,D/AutoSetting( 1500): service - handleMessage() quit looper
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1240): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1240): sku_id=99
D/ContactMessageStore( 1240): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/PMS     (  907): acquireWL(4373cae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=634009, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4373cae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43377dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43377dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43ce2628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43ce2628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=100
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43934ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=694008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43934ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42c11ef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42c11ef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4375ce80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/PMS     (  907): releaseWL(4375ce80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42c47a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=754008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42c47a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44739d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44739d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(446504d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{447beee0: PendingIntentRecord{441068c0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=705745, Int=300000
,V/AlarmManager(  907): sending alarm PendingIntent{42342528: PendingIntentRecord{42a66730 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786213, Int=0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,D/PMS     (  907): releaseWL(446504d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): acquireWL(4429d568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(4429d568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43966728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=814008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43966728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4410d560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4410d560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4466d2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=874008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4466d2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(437679c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(437679c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(446265b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(446265b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43388460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=934008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43388460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(433974c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(433974c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43ab3228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(43ab3228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4319a168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=994008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4319a168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44740e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{428f0930: PendingIntentRecord{42b773e8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452601796878, Int=900000
,W/ContextImpl( 4761): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,V/AlarmManager(  907): sending alarm PendingIntent{420de768: PendingIntentRecord{42c961b8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452601872606, Int=0
,D/PowerUsageService( 4761): call getInstance(),
D/SmartSyncUtils( 4761): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4761): MY_DEBUG = false
D/PMS     (  907): releaseWL(44740e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  907): acquireWL(44182538): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4761 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4761): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4761): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4761): AlarmOnTime = -1
W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/SmartSyncScreenOnOffTimeReceiver( 4761): SettingOnTime = 1452664800000, randomSettingOnTime = 1452661612000
,D/SmartSyncScreenOnOffTimeReceiver( 4761): SettingOffTime = 1452650400000, randomSettingOffTime = 1452656918000
,D/SmartSyncScreenOnOffTimeReceiver( 4761): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4761): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4761): bNightModeTurnOffOnce = false
,D/PMS     (  907): releaseWL(44182538): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(42607ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(42607ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(422fc820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(422fc820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PMS     (  907): runPSCheck
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(432a8500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1054008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(432a8500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43d04bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43d04bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderNotification, total:1
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  907): batLight: plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c80000
D/qdlights(  907): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1601): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,W/ContextImpl( 4761): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  907): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,D/TetherSettings( 4138): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4138): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4138): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4138): Cust_ConnectToPC   : spcsc>false
D/        ( 4138): Cust_ConnectToPC   : IPT>true
D/        ( 4138): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4138): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4138): Index of the first 1 = -1
W/Settings( 4138): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4138): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4138): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4138): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4138): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 4138): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 4138): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42a7e3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): releaseWL(42a7e3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42d17688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1114008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42d17688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4229ebd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4229ebd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43d17910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43d17910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42b784f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1174008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42b784f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(446c62c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(446c62c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(442f3588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1234008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  907): releaseWL(442f3588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43aefa68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/PowerUI ( 1116): closing low battery warning: level=99
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(43aefa68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42b971c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42b971c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42a84148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1294008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42a84148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(428f6960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428f6960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  907): acquireWL(432a3f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1354008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(432a3f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43da14f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=99
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(43da14f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42f63818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42f63818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43dfc750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1414008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43dfc750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4338ea10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4338ea10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderNotification, total:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetPhoneState( 1601): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
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
W/ContextImpl( 4761): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,D/TetherSettings( 4138): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4138): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4138): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4138): Cust_ConnectToPC   : spcsc>false
,D/        ( 4138): Cust_ConnectToPC   : IPT>true
D/        ( 4138): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4138): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4138): Index of the first 1 = -1
W/Settings( 4138): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4138): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4138): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4138): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4138): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 4138): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(437cfe38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(437cfe38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(446dffa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{441f8168: PendingIntentRecord{4323c868 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1461415, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{4382b048: PendingIntentRecord{42ede168 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452602176406, Int=1800000
,D/PMS     (  907): acquireWL(442c5048): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(442c5048): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43397798): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(446dffa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(446c8a88): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43397798): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2179): Aggregate from 1452601425975 (log), 1452600376368 (data)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(446c8a88): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43ca0848): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023391
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023771
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023905
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023908
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023911
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025359
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028195
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029279
,D/PMS     (  907): releaseWL(43ca0848): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=12 [82][10][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43fe92b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1474008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43fe92b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44639908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42342528: PendingIntentRecord{42a66730 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1506252, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{423079e8: PendingIntentRecord{42accab0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1510010, Int=0
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,D/PMS     (  907): acquireWL(446fd3d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(44639908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4324e188): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(446fd3d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(4324e188): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(44622038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44622038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4465a670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1534008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4465a670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43279c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(43279c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4465b2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1594008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4465b2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(447669c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(447669c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4310a920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1654008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4310a920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43cf5b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43cf5b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4373c400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1714008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4373c400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43d8cdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43d8cdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(447034c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1774008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(447034c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(446fb7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(446fb7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(4427ed78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1834008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  907): Prepared write state in 44ms
,I/ProcessStatsService(  907): Prepared write state in 17ms
,I/ProcessStatsService(  907): Prepared write state in 8ms
,D/PMS     (  907): releaseWL(4427ed78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  907): Pruning old procstats: /data/system/procstats/state-2016-01-11-16-25-03.bin
,D/PMS     (  907): acquireWL(42fc7770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{429fc8a0: PendingIntentRecord{42b2afe8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820734, Int=1800000
,D/PMS     (  907): acquireWL(43b307f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{43d0b9e8: PendingIntentRecord{43d21300 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1847722, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{428f0930: PendingIntentRecord{42b773e8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452602696878, Int=900000
,D/PMS     (  907): releaseWL(43b307f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4761): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
D/PMS     (  907): releaseWL(42fc7770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/BatSI   (  907): Couldn't get kernel wake lock stats
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(4348dc88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4348dc88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(44624af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7b60: PendingIntentRecord{426a0fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1894008, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44624af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5062): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5062): ====startRecUseTime====
D/htc.customization.log.level( 5062):  is 
W/CustomizationLogLevel( 5062): Level value is invalid, use default level 2
D/CustomizationManager( 5062):  Read ACC file spent 0.113 (s)
D/CIDMapFileReader( 5062): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5062): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5062): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5062): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5062): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5062): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5062): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5062): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5062): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5062): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5062): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5062): Parsing tag category name = system
I/CustomizationCIDLoader( 5062): Parsing tag category name = application
I/CustomizationCIDLoader( 5062): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5062): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5062): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5062): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5062): Parsing tag category name = Settings
D/CustomizationManager( 5062):  Read CID file spent 0.170 (s)
D/CustomizationManager( 5062):  All configurations done spent 0.170 (s)
W/HtcNativeFlag( 5062): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5062): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5062): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5062): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=5062, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/asset   (  907): Copying FileAsset 0x6ff4a788 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  907): Skipping PackageSetting{42790ff8 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/Launcher( 1275): Deferring update until onResume
D/Launcher( 1275): waitUntilResume // bindAppsRemoved
W/GeofencerStateMachine( 1226): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(4318bcf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4318bcf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/[PluginManager]RegisterService( 4600): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/[PluginManager]RegisterService( 4600): handle notify Blinkfeed plugin client changed
E/ExternalAccountType( 1345): Unsupported attribute readOnly
D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5076 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  907): acquireWL(42bf9d20): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42bf9d20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(429cfa30): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 238 ms] updated apps [took 238 ms] 
W/PackageManager(  907): Unable to load service info ResolveInfo{42f63398 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 5076): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5076): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5076): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5076): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5076): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5076): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5076): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5076): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5076): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5076): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5076): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5076): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5076): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5076): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5076): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5076): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5076): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5076): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5076): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5076): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5076): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5076): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5076): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5076): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5076): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5076): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5076): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5076): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5076): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5076): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5076): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5076): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5076): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5076): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5076): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5076): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5076): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5076): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5076): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5076): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5076): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5076): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5076): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5076): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5076): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5076): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5076): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5076): threadid=11: thread exiting with uncaught exception (group=0x41c9ce30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5076): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5076): Process: com.google.android.apps.docs, PID: 5076
E/AndroidRuntime( 5076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5076): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5076): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5076): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5076): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5076): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 5076): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5076): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5076): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5076): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5076): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5076): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5076): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5076): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5076): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5076): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5076): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5076): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5076): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5076): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5076): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5076): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5076): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5076): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5076): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5076): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 5076): killProcess, pid=5076
D/Process ( 5076): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5094 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
I/ActivityManager(  907): Recipient 5076
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 5076) has died.
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 5094): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 5094): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5094): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5094): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5094): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5094): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5094): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5094): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5094): threadid=10: thread exiting with uncaught exception (group=0x41c9ce30)
E/AndroidRuntime( 5094): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5094): Process: com.android.keychain, PID: 5094
E/AndroidRuntime( 5094): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5094): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5094): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5094): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5094): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5094): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5108 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5094): killProcess, pid=5094
D/Process ( 5094): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452602774063.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 5094
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 5094) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5108): getInstance(Context context)
D/AppTag  ( 5108): getInstance(Context context)
D/AppTag  ( 5108): onCreate()
D/PMS     (  907): acquireWL(42c46ca0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4114 10160 null
D/PMS     (  907): releaseWL(42c46ca0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4153): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2179): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2179): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2179): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2179): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 2179): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2179): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 2179): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2179): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x655e3390
E/DriveAsyncService( 2179): disk I/O error (code 3850)
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
E/SQLiteLog( 2179): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2179): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66d61980
W/dalvikvm( 2179): threadid=50: thread exiting with uncaught exception (group=0x41c9ce30)
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/AndroidRuntime( 2179): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2179): Process: com.google.android.gms, PID: 2179
E/AndroidRuntime( 2179): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2179): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2179): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2179): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2179): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2179): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2179): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2179): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2179): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2179): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2179): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2179): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2179): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
D/Process ( 2179): killProcess, pid=2179
D/Process ( 2179): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2179
I/ActivityManager(  907): Process com.google.android.gms (pid 2179) has died.
D/PMS     (  907): handleWLDeath(429cfa30): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10998ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10997ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10993ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10991ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10990ms
E/SQLiteLog( 1360): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1360): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5cbbf758
W/dalvikvm( 1360): threadid=1: thread exiting with uncaught exception (group=0x41c9ce30)
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1360): FATAL EXCEPTION: main
E/AndroidRuntime( 1360): Process: com.google.process.gapps, PID: 1360
E/AndroidRuntime( 1360): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1360): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1360): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1360): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1360): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1360): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1360): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1360): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1360): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1360): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1360): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1360): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1360): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1360): 	... 10 more
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1360): killProcess, pid=1360
D/Process ( 1360): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5137 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 5137): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5137 dbg=false s=true
I/DeviceManagement( 5137): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5137): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5137): WorkflowService: Starting workflow service
I/DeviceManagement( 5137): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@420ffd88] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5137): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5137): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5137): PackageUpdateWorkflow: ==================================================
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/DeviceManagement( 5137): ModelRegistry: Loading model meta data from resources...
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@42160d10 +
I/Prism.WidgetManager( 1275): onLoadItems() +
I/DeviceManagement( 5137): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5151 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5137): SessionStateController: Checking invariants...
I/ActivityManager(  907): Recipient 1360
I/ActivityManager(  907): Process com.google.process.gapps (pid 1360) has died.
D/WifiService(  907): Client connection lost with reason: 4
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Documents( 5151): Loading roots for com.android.providers.downloads.documents
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20782ms
D/Documents( 5151): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5151): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5151): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5151): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5151): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5151): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5151): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5151): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5151): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5151): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5151): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5151): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5151): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5151): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5151): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5151): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5151): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5151): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5151): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5151): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5151): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5151): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5151): threadid=1: thread exiting with uncaught exception (group=0x41c9ce30)
E/AndroidRuntime( 5151): FATAL EXCEPTION: main
E/AndroidRuntime( 5151): Process: com.android.documentsui, PID: 5151
E/AndroidRuntime( 5151): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5151): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5151): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5151): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5151): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5151): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5151): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5151): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5151): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5151): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5151): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5151): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5151): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5151): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5151): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5151): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5151): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5151): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5151): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5151): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5151): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5151): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5151): 	... 10 more
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5165 uid=10023 gids={50023, 1028, 1015, 1023}
E/ActivityManager(  907): App crashed! Process: com.android.documentsui
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452602774699.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5178 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/Process (  907): killProcessQuiet, pid=4819
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4819:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4902
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
D/Process ( 5151): killProcess, pid=5151
D/Process ( 5151): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Killing 4902:com.htc.aurora/u0a49 (adj 15): empty #17
I/ActivityManager(  907): Recipient 4819
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4902
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 5151
I/ActivityManager(  907): Process com.android.documentsui (pid 5151) has died.
D/ExternalStorage( 5165): After updating volumes, found 1 active roots
E/SQLiteDatabase( 5137): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5137): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5137): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5137): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5137): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5137): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5137): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5137): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.config.model.Co,reConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5137): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5137): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5137): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5137): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 5137): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5137): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5137): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5137): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5137): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5137): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 5137): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5137): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5137): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteDatabase( 5137): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5137): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5137): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5137): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5137): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5137): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 5137): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5137): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5137): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5137): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5137): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5137): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5137): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
