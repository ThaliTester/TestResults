#### Test 5497026179923a9_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1525): handler message = 4011
E/HtcModeClient( 1525): Check connection and retry 12 times. Stop service and kill this process.
D/HtcModeClient( 1525): Don't start project servcice
D/HtcModeClient( 1525): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1525): connectState: CONNECTION_READY = false
D/SilentMusic( 1525): call stop
D/HtcModeClient( 1525): close connection
W/HtcModeClient( 1525): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 1525): read the terminate packet, so break
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  988): doBoolean: SignalStrength 97
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  988):    returned true
E/cutils-trace( 4679): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4679): ====startRecUseTime====
D/htc.customization.log.level( 4679):  is 
W/CustomizationLogLevel( 4679): Level value is invalid, use default level 2
D/CustomizationManager( 4679):  Read ACC file spent 0.080 (s)
D/CIDMapFileReader( 4679): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4679): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4679): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4679): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4679): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4679): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4679): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4679): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4679): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4679): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4679): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4679): Parsing tag category name = system
I/CustomizationCIDLoader( 4679): Parsing tag category name = application
I/CustomizationCIDLoader( 4679): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4679): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4679): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4679): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4679): Parsing tag category name = Settings
D/CustomizationManager( 4679):  Read CID file spent 0.134 (s)
D/CustomizationManager( 4679):  All configurations done spent 0.134 (s)
W/HtcNativeFlag( 4679): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4679): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4679): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4679): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  988): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  988): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  988): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  988): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  988): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  988): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  988): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4679
D/PMS     (  988): acquireHCC(4317cad0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 988 1000 null
D/PMS     (  988): acquireHCC(42bca418): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 988 1000 null
W/asset   (  988): Copying FileAsset 0x639fcf90 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  988): @test_code: getHtcIntentFlag: 0 obj: 1125632384
I/FeedHostManager( 1282): [onPause]
I/FeedProviderManager( 1282): onPause
I/FeedHostManager( 1282): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@422d5d40
I/SocialFeedProvider( 1282): +onPause
I/SocialFeedProvider( 1282): -onPause
D/PMS     (  988): acquireWL(44921930): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 988 1000 null
I/ActivityManager(  988): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4690 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1282): [trimMemory] 20
W/asset   ( 4690): Copying FileAsset 0x5c7c3428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4690): Binding Chromium to main looper Looper (main, tid 1) {4219a528}
I/LibraryLoader( 4690): Expected native library version number "",actual native library version number ""
I/chromium( 4690): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4690): Initializing chromium process, renderers=0
D/BluetoothManagerService(  988): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  988): java.lang.Throwable: stack dump
D/BluetoothManagerService(  988): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@442a8748:true
W/System.err(  988): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  988): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  988): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  988): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  988): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  988): acquireWL(4388c750): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  988): acquireWL(43cd88c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  988): releaseWL(4388c750): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4690): 1109065568: getState(). Returning 12
I/Adreno-EGL( 4690): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4690): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4690): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4690): Local Branch: 
I/Adreno-EGL( 4690): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4690): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4690):                  aa63bbd948f41d15fc72f585e
W/chromium( 4690): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4690): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4690): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4690): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4690): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4690): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4690): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4690): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4690): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4690): CordovaWebView is running on device made by: HTC
,W/AwContents( 4690): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  988): Disable input method client, pid=1282
I/InputMethodManagerService(  988): Enable input method client, pid=4690
W/ResourceType( 4690): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4690): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@421e1610, mServedView=org.apache.cordova.engine.SystemWebView{421a7278 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1218): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1218): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1218): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1218): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  988): Displayed com.test.thalitest/.MainActivity: +298ms
W/AwContents( 4690): nativeOnDraw failed; clearing to background color.
D/PMS     (  988): releaseWL(44921930): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4690): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4690): JniHelper::setJavaVM(0x41d53010), pthread_self() = 1662535184
D/JX-Cordova( 4690): jxcore cordova android initializing
D/WIFI_ICON( 1124): WifiActivity: 0
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  988): acquireWL(4490e780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 988 1000 WorkSource{10074}
V/AlarmManager(  988): sending alarm PendingIntent{42d46d48: PendingIntentRecord{4478c6f0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452509428843, Int=0
I/ActivityManager(  988): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4735 uid=10078 gids={50078}
V/AlarmManager(  988): sending alarm PendingIntent{42c3c4e0: PendingIntentRecord{42c02080 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452509430222, Int=60000
D/PMS     (  988): releaseWL(4490e780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
D/SMSBackup( 4735): SMSBackupAgentService started
D/SMSBackup( 4735): Checking restore status
D/SMSBackup( 4735): Restore complete
D/SMSBackup( 4735): cancelCheckAlarm
D/SMSBackup( 4735): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,I/dalvikvm-heap( 4690): Grow heap (frag case) to 11.557MB for 63974-byte allocation
,I/dalvikvm-heap( 4690): Grow heap (frag case) to 11.618MB for 95956-byte allocation
,I/dalvikvm-heap( 4690): Grow heap (frag case) to 11.706MB for 143930-byte allocation
,I/dalvikvm-heap( 4690): Grow heap (frag case) to 11.821MB for 215890-byte allocation
,D/Finsky  ( 4287): [449] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4287): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  988): killProcessQuiet, pid=4371
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  988): Killing 4371:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  988): Recipient 4371
,I/dalvikvm-heap( 4690): Grow heap (frag case) to 11.999MB for 323830-byte allocation
,I/dalvikvm-heap( 4690): Grow heap (frag case) to 12.662MB for 728606-byte allocation
,I/dalvikvm-heap( 4690): Grow heap (frag case) to 13.256MB for 1092904-byte allocation
,I/dalvikvm-heap( 4690): Grow heap (frag case) to 14.133MB for 1639352-byte allocation
,D/WIFI_ICON( 1124): WifiActivity: 1
,D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4690): Grow heap (frag case) to 15.473MB for 2459024-byte allocation
,W/CpuWake (  988): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  988): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  988): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  988): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  988): >>release mCpuPerf_Freq wakelock
W/CpuWake (  988): <<release mCpuPerf_Freq wakelock
D/PMS     (  988): releaseHCC(4317cad0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  988): releaseHCC(42bca418): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4690): Grow heap (frag case) to 17.470MB for 3688532-byte allocation
,W/jxcore-log( 4690): Initializing JXcore engine
,W/jxcore-log( 4690): JXcore engine is ready
,W/jxcore-log( 4690): Starting JXcore engine
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  988): doBoolean: SignalStrength 97
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  988):    returned true
,W/jxcore-log( 4690): Platform android
W/jxcore-log( 4690): 
,W/jxcore-log( 4690): Process ARCH arm
W/jxcore-log( 4690): 
,D/PMS     (  988): releaseWL(43cd88c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4690): JXcore Cordova bridge is ready!
I/jxcore-log( 4690): 
,W/jxcore-log( 4690): JXcore engine is started
,I/chromium( 4690): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4690): Toggling radios to true
I/jxcore-log( 4690): 
,D/BluetoothAdapter( 4690): enable(): BT is already enabled..!
,D/WifiManager( 4690): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  988): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  988): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  988): Settings:Agentvalue: 2
W/Settings:Agent(  988): >> traceCallingStack()
W/Settings:Agent(  988): Process.myPid(): 988
W/Settings:Agent(  988): Process.myTid(): 1367
W/Settings:Agent(  988): Process.myUid(): 1000
W/Settings:Agent(  988): 
W/Settings:Agent(  988): 
W/System.err(  988): java.lang.Throwable: stack dump
W/System.err(  988): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  988): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  988): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  988): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  988): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  988): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  988): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  988): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  988): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  988): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  988): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  988): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  988): 
,W/Settings:Agent(  988): << traceCallingStack(): 1(ms)
,D/WifiManager( 4690): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  988): doBoolean: DISCONNECT
D/WifiManager( 4690): reconnect: Base Package Name=com.test.thalitest, uid=10389
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): TDLS: Tear down peers
,I/wpa_supplicant( 1167): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4690): Radios toggled
I/jxcore-log( 4690): 
D/WifiService(  988): New client listening to asynchronous messages
D/WifiService(  988): setWifiEnabled: true pid=4690, uid=10389
E/WifiService(  988): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  988): isSprintWifiRestricted(): false
I/WifiService(  988): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  988): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4690): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4690): 
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1167): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1167): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  988): interfaceLinkStateChanged wlan0, false
D/Tethering(  988): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1167): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  988): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  988): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  988): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  988): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  988): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  988): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  988): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  988): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  988): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  988): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  988): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
,D/Tethering(  988): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1167): TDLS: Remove peers on disassociation
D/Tethering(  988): interfaceLinkStateChanged wlan0, false
D/Tethering(  988): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8892bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1167):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1167): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1167): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1167): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  988): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  988):    returned true
D/WifiPerfLock(  988): release()
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  988): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  988): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiStateMachine(  988): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  988): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  988):    returned true
D/WifiNative-wlan0(  988): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  988):    returned true
D/ConnectivityService(  988): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  988): acquireWL(4368bd20): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 988 1000 null
D/WifiP2pService(  988): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  988): [RunningState] Stop DHCP
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/libc    (  988): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  988): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  988): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  988): doBoolean: RECONNECT
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): Fast associate: Old scan results
I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): State: DISCONNECTED -> SCANNING
,I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
D/libc    (  988): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  988): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  988): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  988): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  988):    returned true
D/WifiDataStallTracker(  988): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  988): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  988): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  988): stopDataStallAlarm: current tag=24662 mDataStallAlarmIntent=PendingIntent{42bfd488: PendingIntentRecord{42cbd378 android broadcastIntent}}
I/IntentController( 1124): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  988): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  988):    returned true
,D/WifiNative-wlan0(  988): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  988):    returned true
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
D/WIFI_ICON( 1124): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  988): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  988): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/WifiP2pService(  988): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  988): Provision feature enable=false
,D/ConnectivityService(  988): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiStateMachine(  988): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  988): Exit handleNetworkDisconnect
,D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent DefaultState
D/UsbnetStateTracker(  988): isAvailable+-
D/UsbnetStateTracker(  988): reconnect
D/UsbnetStateTracker(  988): isAvailable+-
,D/WISPrService( 3988): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/ConnectivityService(  988): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  988): default: reconnect()
D/MDST    (  988): default: setTeardownRequested(false)
,D/MDST    (  988): default: setEnableApn apnType =default , enable=true
D/WifiDataStallTracker(  988): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  988): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1124): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  988): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3988): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateTracker(  988): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent,
D/WifiService(  988): New client listening to asynchronous messages
D/ConnectivityService(  988): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  988): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  988): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/WISPrService( 3988): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3988): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  988): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,V/NativeCrypto( 1376): Read error: ssl=0x662bb398: I/O error during system call, Connection timed out
W/ConnectivityService(  988): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  988): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  988): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  988): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  988): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1124): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  988): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  988): handleConnectivityChange: resetting
D/ConnectivityService(  988): resetConnections(wlan0, 3)
,D/PMS     (  988): acquireWL(42ae7740): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,V/NativeCrypto( 1376): SSL shutdown failed: ssl=0x662bb398: I/O error during system call, Broken pipe
D/libc    (  365): [NET] entry_id:6   entry:0xb869fd08  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb869fc20  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb869fb20  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb86a8db8  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb86a4370  removed 
D/libc    (  365): [NET] entry_id:9   entry:0xb86a4270  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb86a8f70  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb86a8cf8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb86a4458  removed 
D/libc    (  365): [NET] entry_id:10   entry:0xb869f988  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/ConnectivityService(  988): flush DNS cache for net 1(wlan0)
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
D/Nat464Xlat(  988): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  988): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
D/ConnectivityService(  988): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
D/ConnectivityService(  988): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  988): acquireWL(42372680): PARTIAL_WAKE_LOCK  NetworkStats 0x1 988 1000 null
D/ConnectivityService(  988): getNetworkInfo networkType=1 called by  (988/1000)
,D/WirelessDisplayService(  988): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  988): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1124): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiStateMachine(  988): startScan Pid: 988 Uid 1000
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/ConnectivityService(  988): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  988): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  988): reportInetCondition for net -1, percentage: 0 by  (1376/10029)
,D/WifiNative-wlan0(  988): doBoolean: SCAN
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  988):    returned false
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/BatSI   (  988): WIFI scan started for: 650a0301 uid:1000
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/PMS     (  988): releaseWL(42ae7740): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,I/QuickSettingWifi( 1124): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  988): releaseWL(42372680): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  988): mActiveDefaultNetwork: -1
D/ConnectivityService(  988): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  988): Waited long enough for: ServiceRecord{442f0b40 u0 com.htc.htclocationservice/.AutoSettingService}
,V/Tethering(  988): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/CaptivePortalTracker(  988): DelayedCaptiveCheckState
D/CaptivePortalTracker(  988): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  988): NoActiveNetworkState
D/Tethering(  988): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  988): bSetPropertyMultiRAB:false
,I/NetworkMonitor( 4041): type=WIFI subType= reason=null isConnected=false
,D/htcCheckinService(  988): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/ConnectivityService(  988): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  988): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  988): getNetworkInfo networkType=1 called by  (988/1000)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/PMS     (  988): acquireWL(4405b6d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 988 1000 null
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (1232/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (1232/10029)
D/ConnectivityService(  988): getNetworkInfo networkType=1 called by com.google.android.music (4041/10154)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.apps.docs (4509/10100)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/ConnectivityService(  988): getNetworkInfo networkType=1 called by com.htc.launcher (1282/10076)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/htcCheckinService(  988): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/Tethering(  988): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  988): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  988): ipv4Default null
I/Tethering(  988): No IPv4 upstream interface, giving up.
D/Tethering(  988): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1282): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.apps.docs (4509/10100)
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
D/ConnectivityService(  988): getActiveNetworkInfo called by  (2831/10021)
,I/ActivityManager(  988): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4756 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  988): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  988): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  988): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  988): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  988): releaseWL(4405b6d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4756): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4756): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4756): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4756): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4756): Preparing secondary program dexes.
V/DexLibLoader( 4756): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4756): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4756): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4756): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4756): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4756): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4756): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4756): Dex already copied
D/OdexVerifier( 4756): Odex verification is skipped.
,V/DexLibLoader( 4756): Creating class loader
,V/DexLibLoader( 4756): Finished creating class loader,
V/DexLibLoader( 4756): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4756): Dex already copied
D/OdexVerifier( 4756): Odex verification is skipped.
,V/DexLibLoader( 4756): Creating class loader,
V/DexLibLoader( 4756): Finished creating class loader,
V/DexLibLoader( 4756): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4756): Dex already copied
D/OdexVerifier( 4756): Odex verification is skipped.
,V/DexLibLoader( 4756): Creating class loader,
V/DexLibLoader( 4756): Finished creating class loader,
V/DexLibLoader( 4756): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4756): Dex already copied
D/OdexVerifier( 4756): Odex verification is skipped.
,V/DexLibLoader( 4756): Creating class loader
,V/DexLibLoader( 4756): Finished creating class loader
,V/DexLibLoader( 4756): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4756): DexLibLoader.ensureDexLoaded took 19 ms
,I/SensorManager(  988): mEventCount = 1050
,W/dalvikvm( 4756): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4756): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4756): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4756): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4756): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4756): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4756): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4756): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,V/LightsService(  988): setLight #0: color=#3d
,W/dalvikvm( 4756): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-83
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1167): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1167): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1167): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 3
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 1
I/wpa_supplicant( 1167): wpa_s->is_screen_on 1
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): selected network = 2
D/wpa_supplicant( 1167): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb88944e8  current_ssid=0x0
D/wpa_supplicant( 1167): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1167): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1167): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1167): check if in concurrent case
,I/wpa_supplicant( 1167): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1167): RSN: PMKSA cache search - network_ctx=0xb88944e8 try_opportunistic=0
D/wpa_supplicant( 1167): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1167): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1167): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1167): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1167): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1167): nl80211: Unsubscribe mgmt frames handle 0xb8893718 (mode change)
D/wpa_supplicant( 1167): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8893718
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb8893718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb8893718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb8893718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb8893718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb8893718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb8893718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb8893718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb8893718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb8893718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb8893718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1167):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1167):   * freq=2412
D/wpa_supplicant( 1167):   * Auth Type 0
D/wpa_supplicant( 1167):   * WPA Versions 0x2
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1167): nl80211: Connect request send successfully
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  988): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  988): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (489) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-47
I/wpa_supplicant( 1167): tsf=0000000105961125
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000105961138
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000105961144
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-83
I/wpa_supplicant( 1167): tsf=0000000105961148
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  988): getDiscoveryDongleList
D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (4) end of scan result ==
,D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/WifiManager( 1232): getScanResults enter 
D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (4) end of scan result ==
W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 105961125, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 105961138, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 105961144, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2452, timestamp: 105961148, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): add 4 to mScanResults
D/BatSI   (  988): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,V/LightsService(  988): setLight #0: color=#39
,V/LightsService(  988): setLight #0: color=#33
,E/FbInjectorInitializer( 4756): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,V/LightsService(  988): setLight #0: color=#29
,V/LightsService(  988): setLight #0: color=#25
,D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/Tethering(  988): interfaceLinkStateChanged wlan0, false
D/Tethering(  988): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1167): nl80211: Connect event
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1167): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  988): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1167): Add randomness: count=11 entropy=4
I/wpa_supplicant( 1167): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1167): TDLS: Remove peers on association
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1167): EAPOL: enable timer tick
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
D/Tethering(  988): interfaceLinkStateChanged wlan0, true
D/Tethering(  988): interfaceStatusChanged wlan0, true
D/Tethering(  988): [isWifi] getHotspotEnabled: false
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  988): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  988): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  988): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  988): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  988): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  988): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  988): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  988): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  988): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  988): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  988): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  988): Enter handleAss,ociatedWithEvent
D/WifiStateMachine(  988): Associated
D/WifiStateMachine(  988): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  988): Exit handleAssociatedWithEvent
I/wpa_supplicant( 1167): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1167): Get randomness: len=32 entropy=5
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  988): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  988): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  988): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  988): updateConnectedAP...
D/WifiApDatabaseHandler(  988): updateConnectedAP...
D/WifiStateMachine(  988): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  988): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  988): This record is existed, only update it...
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  988): updateConnectedAP...
I/wpa_supplicant( 1167): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb88939f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1167):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1167): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f2cb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1167):    broadcast key
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1167): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1167): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1167): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1167): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1167): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1167): set send_ind_to_ndc = 0
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1167): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1167): EAPOL authentication completed successfully
I/wpa_supplicant( 1167): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  988): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  988): interfaceLinkStateChanged wlan0, true
D/Tethering(  988): interfaceStatusChanged wlan0, true
D/WifiMonitor(  988): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/Tethering(  988): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  988): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  988): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  988): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  988): updateConnectedAP...
V/LightsService(  988): setLight #0: color=#1f
D/WifiStateMachine(  988): fetchFrequency(), freq = 2412
D/WifiStateMachine(  988): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  988): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  988): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  988): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  988): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiApDatabaseHandler(  988): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  988): This record is existed, only update it...
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  988): updateConnectedAP...
I/IntentController( 1124): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 3988): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  988): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  988): Provision feature enable=false
D/ConnectivityService(  988): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1124): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3988): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  988): updateConnectedAP...
V/LightsService(  988): setLight #0: color=#15
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
D/WifiStateMachine(  988): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
D/DhcpStateMachine(  988): [StoppedState] Start DHCP
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  988): doBoolean: SignalStrength 97
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  988):    returned true
,D/WifiNative-wlan0(  988): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
W/fb4a(:<default>):StaticBindingVerifier( 4756): Verify
D/WifiNative-wlan0(  988):    returned true
D/WifiNative-wlan0(  988): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 1
,I/wpa_supplicant( 1167): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  988):    returned true
D/WifiNative-wlan0(  988): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  988):    returned null
E/WifiStateMachine(  988): Unexpected BatchedScanResults :null,
D/WifiNative-wlan0(  988): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  988):    returned null
D/WifiStateMachine(  988): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  988): acquireWL(44055828): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 988 1000 null
D/WifiStateMachine(  988): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  988): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4298bcb0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4298bcb0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1124): receive.wifiConnect:false wifiAPname:null elapse:1
V/LightsService(  988): setLight #0: color=#14
,D/WifiService(  988): New client listening to asynchronous messages
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4756): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4756): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  988): killProcessQuiet, pid=4478
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  988): Killing 4478:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  988): Recipient 4478
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AutoSetting( 1321): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  988): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4784 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
,D/AutoSetting( 1321): Util - no network available!
,D/AutoSetting( 1321): service - onCreate()
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
D/AutoSetting( 1321): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  988): request 4265fba8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  988): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1321): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1321): service - mHandler: cancel location update
D/AutoSetting( 1321): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4784): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4784): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4784): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4784): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  988): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4800 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,W/fb4a(:<default>):UserScope( 4756): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4756): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.setupwizard (4784/10079)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.setupwizard (4784/10079)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.setupwizard (4784/10079)
,W/fb4a(:<default>):UserScope( 4756): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4756): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  988): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4816 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  988): killProcessQuiet, pid=4509
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  988): Killing 4509:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,E/dalvikvm( 4756): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4756): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4756): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4756): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4756): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4756): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4756): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4756): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4756): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4756): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4756): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,I/ActivityManager(  988): Recipient 4509
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4816): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4816): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4816): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4816): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4816): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4756): Grow heap (frag case) to 9.962MB for 84664-byte allocation
W/dalvikvm( 4756): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4756): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4756): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4756): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4756): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4756): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4756): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 10.017MB for 39954-byte allocation
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 10.093MB for 79892-byte allocation
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.apps.magazines (4816/10151)
,V/WebViewChromiumFactoryProvider( 4816): Binding Chromium to main looper Looper (main, tid 1) {42191ea8}
,I/LibraryLoader( 4816): Expected native library version number "",actual native library version number ""
,I/chromium( 4816): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4816): Initializing chromium process, renderers=0
,D/PMS     (  988): acquireWL(4404ae50): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  988): acquireWL(442a9a98): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4816): BLUETOOTH permission is missing!
D/PMS     (  988): releaseWL(4404ae50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4816): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4816): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4816): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4816): Local Branch: 
I/Adreno-EGL( 4816): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4816): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4816):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4816): Starting up...
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.apps.magazines (4816/10151)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.apps.magazines (4816/10151)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.apps.plus (4263/10160)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.apps.plus (4263/10160)
,D/Process (  988): killProcessQuiet, pid=4532
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  988): Killing 4532:com.htc.backup/1000 (adj 15): empty #17
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 10.280MB for 75760-byte allocation
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,I/iu.Environment( 2187): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2187): num queued entries: 0
,I/iu.UploadsManager( 2187): num updated entries: 0
,I/iu.SyncManager( 2187): NEXT; no task
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
W/BroadcastQueue(  988): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42dd8f10 u0 ReceiverList{42dbe1a0 4756 com.facebook.katana/10027/u0 remote:42c84790}}
W/BroadcastQueue(  988): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42dd8f10 u0 ReceiverList{42dbe1a0 4756 com.facebook.katana/10027/u0 remote:42c84790}}
W/BroadcastQueue(  988): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44088bc0 u0 ReceiverList{44088b60 4756 com.facebook.katana/10027/u0 remote:44058f50}}
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/PMS     (  988): acquireWL(43de4c80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): releaseWL(43de4c80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  988): Recipient 4532
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4756): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4756): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1167): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1167): EAPOL: disable timer tick
,D/libc    (  988): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  988): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  988): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  988): [NET] getaddrinfo-, SUCCESS
D/libc    (  988): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  988): [NET] getaddrinfo-, SUCCESS
D/libc    (  988): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  988): [NET] getaddrinfo-, SUCCESS
D/libc    (  988): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  988): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  988): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  988):    returned true
,D/WifiNative-wlan0(  988): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  988):    returned true
,D/WifiStateMachine(  988): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  988): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  988): releaseWL(44055828): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1167): Change stage from stage0 to stage3
,D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  988): doBoolean: SignalStrength 97
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  988):    returned true
,D/WifiStateMachine(  988): gateway: /192.168.1.1
,D/WifiNative-wlan0(  988): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1167): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  988):    returned true
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  988): VerifyingLinkState enter
,D/WifiStateMachine(  988): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  988): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  988): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1124): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  988): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  988): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  988): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  988): startDataStallAlarm: tag=24664 delay=15s
,I/IntentController( 1124): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  988): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1124): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  988): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  988): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  988): Provision feature enable=false
,D/WifiWatchdogStateMachine(  988): WAN detection
,D/WISPrService( 3988): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
D/libc    (  988): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  988): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  988): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  988): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  988): default: teardown()
D/MDST    (  988): default: setTeardownRequested(true)
D/MDST    (  988): default: setEnableApn apnType =default , enable=false
D/MDST    (  988): default: setTeardownRequested(true)
D/ConnectivityService(  988): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  988): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b1cab0
D/ConnectivityService(  988): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  988): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  988): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  988): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  988): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  988): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  988): handleConnectivityChange: resetting
D/Nat464Xlat(  988): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  988): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  988): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  988): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  988): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  988): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  988): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  988): acquireWL(432b6dc0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 988 1000 null
D/ConnectivityService(  988): getNetworkInfo networkType=1 called by  (988/1000)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.setupwizard (4784/10079)
D/WirelessDisplayService(  988): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  988):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/PMS     (  988): acquireWL(43c08e00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I/QuickSettingWifi( 1124): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/CheckinService( 2187): Checkin interval check for package: unspecified last checkin: 1452509393032 min interval config: 0 actual interval: 43978
D/PMS     (  988): acquireWL(440a7e38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): releaseWL(43c08e00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2187): Checking schedule, now: 1452509437017 next: 1452509423008
,I/CheckinService( 2187): active receiver: enabled
,I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2187, uid=10029, userID:0
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2187): Preparing to send checkin request
,I/EventLogService( 2187): Accumulating logs since 1452509388998
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  988): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/PMS     (  988): releaseWL(432b6dc0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2187): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  988): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2187): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  988): getNetworkInfo networkType=9 called by com.google.android.gms (2187/10029)
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  988): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4891 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4891): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4891): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4891): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4891): install
,I/MultiDex( 4891): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4891): loading existing secondary dex files
,I/MultiDex( 4891): load found 3 secondary dex files
,I/MultiDex( 4891): install done
,W/dalvikvm( 4891): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4891): VFY: unable to resolve instance field 36
,W/dalvikvm( 4891): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4891): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4891): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1232): callingUid 10029, callindPid: 1232
,D/LocationInitializer( 2187): Restart initialization of location
,W/dalvikvm( 4891): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4891): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/AuthorizationBluetoothService( 1376): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1376): Proximity feature is not enabled.
,W/dalvikvm( 4891): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/MDM     ( 1232): [121] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/dalvikvm( 4891): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4891): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4891): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4891): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  988): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  988): Resuming delayed broadcast
,W/GCoreFlp( 1232): No location to return for getLastLocation()
,W/FusedLocationProvider( 1232): location=null
D/PMS     (  988): acquireWL(43097e28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): releaseWL(43097e28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2427678944
,D/NativeLibraryUtils( 4891): Install completed successfully. count=14 extracted=0
,I/WVCdm   (  372): CdmEngine::CloseSession
,W/Settings( 4891): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WIFI_ICON( 1124): WifiActivity: 3
,D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  988): releaseWL(4368bd20): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  988): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  988): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  988): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  988): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  988): bSetPropertyMultiRAB:false
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,D/ConnectivityService(  988): getNetworkInfo networkType=1 called by  (988/1000)
D/Tethering(  988): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  988): NoActiveNetworkState
,D/CaptivePortalTracker(  988): DelayedCaptiveCheckState
I/Tethering(  988): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  988): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  988): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  988): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  988): Found interface wlan0
,D/Tethering(  988): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4041): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (1232/10029)
D/PMS     (  988): acquireWL(443ad0c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 988 1000 null
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.setupwizard (4784/10079)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
D/ConnectivityService(  988): getNetworkInfo networkType=1 called by com.google.android.music (4041/10154)
D/ConnectivityService(  988): getNetworkInfo networkType=1 called by com.htc.launcher (1282/10076)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.htc.musicenhancer (4123/10053)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (1232/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/htcCheckinService(  988): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  988): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1282): [onReceive] WIFI(1): CONNECTED
,D/AccTypeManager( 1348): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,I/Adreno-EGL( 4891): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4891): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4891): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4891): Local Branch: 
I/Adreno-EGL( 4891): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4891): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4891):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (2831/10021)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,W/AccTypeManager( 1348): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1348): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1321): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4784): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4784): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1321): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1321): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1321): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1321): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1321): service - handleMessage() setting current location null
D/AutoSetting( 1321): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1321): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  988): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
,E/ExternalAccountType( 1348): Unsupported attribute readOnly
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.apps.magazines (4816/10151)
,I/Adreno-EGL( 4891): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4891): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4891): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4891): Local Branch: 
I/Adreno-EGL( 4891): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4891): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4891):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.apps.plus (4263/10160)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.apps.plus (4263/10160)
,I/CheckinService( 2187): Checkin interval check for package: unspecified last checkin: 1452509393032 min interval config: 0 actual interval: 45073
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  988): acquireWL(437d38b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): releaseWL(437d38b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2187, uid=10029, userID:0
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,I/iu.Environment( 2187): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2187): num queued entries: 0
,I/iu.UploadsManager( 2187): num updated entries: 0
,I/iu.SyncManager( 2187): NEXT; no task
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1376): [NET] getaddrinfo-,err=8
D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1376): [NET] getaddrinfo-, 1
,D/libc    ( 1376): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =3a9 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/GpsLocationProvider(  988): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  988): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  988): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  988): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  988): acquireWL(439f5330): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/PMS     (  988): acquireWL(443667b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 988 1000 null
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
D/PMS     (  988): releaseWL(443667b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  988): releaseWL(443ad0c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/dalvikvm-heap( 4263): Grow heap (frag case) to 13.521MB for 1821008-byte allocation
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (4891/10029)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 206
,D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1376): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1376): [NET] getaddrinfo-,err=8
,D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1376): [NET] getaddrinfo-,err=8
,I/Adreno-EGL( 4891): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4891): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4891): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4891): Local Branch: 
I/Adreno-EGL( 4891): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4891): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4891):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=14 [7][1][0]
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  988): BroadcastRSSIForIMS, newrssi =-55 , oldRssi= -200
D/WifiNative-wlan0(  988): doBoolean: SignalStrength 97
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1124): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiNative-wlan0(  988):    returned true
,W/fb4a(:<default>):UserScope( 4756): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4756): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,D/PMS     (  988): acquireWL(442e6370): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,D/PMS     (  988): releaseWL(439f5330): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  988): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
D/ConnectivityService(  988): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  988): handleInetConditionChange: starting a change hold
,D/PMS     (  988): releaseWL(442e6370): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(43149ad8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  988): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
D/ConnectivityService(  988): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  988): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  988): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
D/ConnectivityService(  988): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  988): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
D/PMS     (  988): releaseWL(43149ad8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2159990747
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2187): Classify the device as Phone.
,E/fb4a(:<default>):LocalFbBroadcastManager( 4756): Called registerBroadcastReceiver twice.
,D/libc    ( 2187): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2187): [NET] getaddrinfo-,err=8
D/libc    ( 2187): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2187): [NET] getaddrinfo-, 1
,D/libc    ( 2187): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e9de +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 227
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2187): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2187): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2187): [NET] getaddrinfo-,err=8
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,D/libc    ( 2187): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2187): [NET] getaddrinfo-,err=8
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/libc    ( 2187): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2187): [NET] getaddrinfo-,err=8
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,I/CheckinTask( 2187): Sending checkin request (12081 bytes)
,D/PMS     (  988): releaseWL(442a9a98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  988): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  988): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  988): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=15 [19][3][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2187): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  988): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2187): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  988): getNetworkInfo networkType=9 called by com.google.android.gms (2187/10029)
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,I/CheckinRequestBuilder( 2187): Classify the device as Phone.
,I/CheckinTask( 2187): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2187): Checking schedule, now: 1452509439286 next: 1453032376282
,I/CheckinService( 2187): active receiver: disabled
I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2187, uid=10029, userID:0
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
I/CheckinService( 2187): Checking schedule, now: 1452509439302 next: 1453032376282
,I/CheckinService( 2187): active receiver: disabled
,D/CheckinService( 2187): Recording last checkin time for package unspecified as 1452509439308
I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2187, uid=10029, userID:0
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/PMS     (  988): releaseWL(440a7e38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,D/GCM     ( 1376): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  988): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  988): [NET] getaddrinfo-,err=8
,D/libc    (  988): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  988): [NET] getaddrinfo-, 1
D/libc    (  988): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f2f7 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  988): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  988): Find DNS Address www.htc.com/104.81.130.175
,I/GAV2    ( 4816): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  988): doBoolean: SignalStrength 97
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  988):    returned true
D/WIFI_ICON( 1124): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiStateMachine(  988): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  988): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  988): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent DefaultState
,I/jxcore-log( 4690): Test app app.js loaded
I/jxcore-log( 4690): 
,I/Choreographer( 4690): Skipped 526 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4690): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/PMS     (  988): Going to sleep due to screen timeout...
,I/SensorManager(  988): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@429065c8
W/SensorService(  988): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  988): disable: get sensor name = CM36282 Light sensor
W/SensorService(  988): pid=988, uid=1000
W/SensorService(  988): Active sensors: size = 2
W/SensorService(  988): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  988): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  988): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@429065c8, eanble = 0, strlen(mName) = 59
W/SensorService(  988): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  988): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427a4d30
W/SensorService(  988): Listener[1] = com.htc.smartdim.sensor_eye@43368928
,W/SensorService(  988): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  988): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  988): Couldn't get kernel wake lock stats
V/LightsService(  988): setLight #2: color=#0
D/qdlights(  988): set_light_buttons_func: on=0 brightness=0
V/LightsService(  988): setLight #0: color=#0
,W/PMS     (  988): mWirelessDisplayManager is null
D/WirelessDisplayService(  988): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  988): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  988): Excessive delay in blankDisplay() while turning screen off: 322ms
D/PMS     (  988): nativeSetInteractive:false
,D/PMS     (  988): nativeSetInteractive:false done
,D/PMS     (  988): nativeSetAutoSuspend:true
,D/PMS     (  988): nativeSetAutoSuspend:true done
D/HABCtrl (  988): TPE algorithm. remove timeout.
D/PMS     (  988): OOBE c monitor 11
,I/InputManager(  988): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  988): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  988): Disable input method client, pid=4690
D/NfcService( 1264): ScreenObserver: OFF
,D/NfcService( 1264): applyRouting - 0
D/NfcService( 1264): applyRouting -2
,I/IntentController( 1124): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/ResourceType( 4690): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4690): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{421a7278 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  988): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@430a94b0)
D/PMS     (  988): acquireWL(43757ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  988): n_update end
D/PMS     (  988): acquireWL(43a58df0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1264 1027 null
D/PMS     (  988): releaseWL(43757ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  988): wakingUp
,V/KeyguardServiceDelegate(  988): **** SHOWN CALLED ****
D/PMS     (  988): releaseWL(43a58df0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  988): No lock screen! windowToken=null
,D/PMN     (  988): onScreenOn
,I/IntentController( 1124): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  988): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1124): closing low battery warning: level=100
D/PowerUI ( 1124): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WirelessDisplayService(  988): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  988): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  988): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
,I/HtcPowerSaver(  988): >> updateStatus
D/MtpService( 2831): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2831): [MTP][onReceive]-
,D/NfcService( 1264): applyRouting - 0
,D/NfcService( 1264): applyRouting -2
,D/AutoSetting( 1321): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  988): acquireWL(42ce22f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1264 1027 null
D/PMS     (  988): releaseWL(42ce22f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
D/AlarmManager(  988): ACTION_SCREEN_ON
I/AlarmManager(  988): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  988): [AlarmQueuing] done recovering
I/AlarmManager(  988): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  988): [AlarmQueuing] done EPS screen off alarm recovering
D/AutoSetting( 1321): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3988): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3988): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3988): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3988): Cust_ConnectToPC   : spcsc>false
D/        ( 3988): Cust_ConnectToPC   : IPT>true
D/        ( 3988): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3988): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3988): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3988): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3988): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/ClockThread( 1124): stop update clock
D/WirelessDisplayService(  988): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  988): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  988): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  988): onReceive: action=android.intent.action.SCREEN_ON
V/NotificationService(  988): batLight: Full, plugged
V/LightsService(  988): setLight #8: color=#c8c800
D/qdlights(  988): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  988): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  988): setLight #8: color=#c800
D/qdlights(  988): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  988): [LedInfo] has indicator attribute
D/qdlights(  988): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  988): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiDataStallTracker(  988): startDataStallAlarm: tag=24665 delay=15s
,I/PSReceiver( 3988): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3988): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3988): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3988):  defaultType:0
D/WifiNative-wlan0(  988): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): SET_SCREEN_ON:On
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +,	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1167): BG scan when screen On
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): Match BG scan, scan!
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  988):    returned true
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/ContextImpl( 3988): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917,
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/BatteryController( 1124): status:5 level:100 unsupport:false plugged:true
,V/SRS_Proc(  372): ParamSet string: screen_state=on
V/NotificationService(  988): batLight: Full, plugged
V/LightsService(  988): setLight #8: color=#c8c800
D/qdlights(  988): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  988): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  988): setLight #8: color=#c800
D/qdlights(  988): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  988): [LedInfo] has indicator attribute
D/qdlights(  988): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  988): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  988): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/NetworkPolicy(  988): updateScreenOn: false
,I/ActivityManager(  988): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4946 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  988): acquireWL(447c23f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  988): releaseWL(447c23f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(4477cbc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  988): releaseWL(4477cbc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1783): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1783): onScreenOn: 1452509442744
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1783): onScreenOn: 1452509442744
,I/SensorManager(  988): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427a4d30
W/SensorService(  988): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  988): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  988): pid=988, uid=1000
W/SensorService(  988): Active sensors: size = 2
W/SensorService(  988): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  988): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  988): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427a4d30, eanble = 0, strlen(mName) = 91
W/SensorService(  988): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  988): Listener[0] = com.htc.smartdim.sensor_eye@43368928
,W/SensorService(  988): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4946): isEpsOn(), nState = 0
D/PMS     (  988): acquireWL(44359f18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4946 1000 null
D/PMN     (  988): goingToSleep
D/PMS     (  988): acquireWL(43c8a1b0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 988 1000 null
,D/PMS     (  988): releaseWL(44359f18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
D/PMS     (  988): releaseWL(43c8a1b0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/AlarmManager(  988): ACTION_SCREEN_OFF
I/AlarmManager(  988): [AlarmQueuing] screen off now: 
I/AlarmManager(  988): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  988): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  988): stopDataStallAlarm: current tag=24665 mDataStallAlarmIntent=PendingIntent{42ce8b60: PendingIntentRecord{42cbd378 android broadcastIntent}}
,D/WifiNative-wlan0(  988): doBoolean: SET_SCREEN_ON 0
I/AlarmManager(  988): [AlarmQueuing] wifi connection: true
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
D/PMS     (  988): acquireWL(42b07ab0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 988 1000 null
,D/SmartSyncUtils( 4946): getMobilePolicyEnabled, result = true
,D/Process (  988): killProcessQuiet, pid=4496
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  988): Killing 4496:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  988): Recipient 4496
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): SET_SCREEN_ON:Off
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1167): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiStateMachine(  988): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
,D/WifiNative-wlan0(  988):    returned true
,D/WifiNative-wlan0(  988): doBoolean: SignalStrength 97
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1124): updateWifiState: RSSI_CHANGED 3 -> 3
,D/WifiNative-wlan0(  988):    returned true
,D/WifiStateMachine(  988): [ScoreAP] + current TXpacket:37, mTXpacketCount:0, avgLinkspeed:72,mAvgTxRate54
,D/WifiStateMachine(  988): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  372): ParamSet string: screen_state=off
W/ContextImpl( 4946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4946): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4946): getMobilePolicyEnabled, result = true
D/NetworkPolicy(  988): updateScreenOn: false
D/WifiService(  988): New client listening to asynchronous messages
,D/ContactMessageStore( 1248): start background delete task...
,D/SmartSyncUtils( 4946): isEpsOn(), nState = 0
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,I/SensorManager(  988): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@43368928
,W/SensorService(  988): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  988): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  988): pid=988, uid=1000
W/SensorService(  988): Active sensors: size = 1
W/SensorService(  988): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  988): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@43368928, eanble = 0, strlen(mName) = 36
W/SensorService(  988): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  988): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  988): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  988): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  988): pid=988, uid=1000
W/SensorService(  988): Active sensors: size = 0
W/SensorService(  988): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@43368928, eanble = 0, strlen(mName) = 36
W/SensorService(  988): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  988): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  988): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@43368928
E/ActivityThread(  988): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42de05f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  988): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42de05f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  988): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  988): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  988): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  988): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  988): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  988): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  988): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  988): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  988): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  988): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  988): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  988): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  988): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  988): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  988): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  988): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  988): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  988): acquireWL(42d3a380): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
D/PMS     (  988): releaseWL(42d3a380): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): acquireWL(43d5d2b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): releaseWL(43d5d2b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1783): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1783): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1783): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1783): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1783): onScreenOff
,D/AutoSetting( 1321): service - mHandler: cancel location update
,D/AutoSetting( 1321): service -           changes count: 0
,D/Process (  988): killProcessQuiet, pid=4549
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  988): Killing 4549:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  988): Recipient 4549
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  988):    returned true
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/PMS     (  988): releaseWL(42b07ab0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=12 entropy=0
D/wpa_supplicant( 1167): Add randomness: count=13 entropy=1
D/wpa_supplicant( 1167): Add randomness: count=14 entropy=2
D/wpa_supplicant( 1167): Add randomness: count=15 entropy=3
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431,
D/wpa_supplicant( 1167): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700',
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
,I/wpa_supplicant( 1167): wpa_s->wpa_state is 9,
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
,I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=16 entropy=4
D/wpa_supplicant( 1167): Add randomness: count=17 entropy=5
D/wpa_supplicant( 1167): Add randomness: count=18 entropy=6
D/wpa_supplicant( 1167): Add randomness: count=19 entropy=7
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: DISCONNECTED -> INACTIVE
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  988): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  988): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiMonitor(  988): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (489) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-47
I/wpa_supplicant( 1167): tsf=0000000115589113
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000115589139
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000115589150
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000115589160
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  988): getDiscoveryDongleList
D/WifiP2pService(  988): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  988): InactiveState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4400f948 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4400f948 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@4400f948 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 115589113, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  988): Only print Top 10 in ApScanList
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 115589139, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 115589150, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 115589160, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): add 4 to mScanResults
V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  988):  + computeScore(NG700): 1
D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (4) end of scan result ==
D/WifiManager( 1232): getScanResults enter 
D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (4) end of scan result ==
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  988): getDiscoveryDongleList
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 10.944MB for 16444-byte allocation
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 10.976MB for 36988-byte allocation
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 11.005MB for 55478-byte allocation
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 11.011MB for 43018-byte allocation
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 11.055MB for 65548-byte allocation
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 11.062MB for 44258-byte allocation
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 11.094MB for 57408-byte allocation
,D/libc    ( 4756): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4756): [NET] getaddrinfo-,err=8
D/libc    ( 4756): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4756): [NET] getaddrinfo-, 1
,D/libc    ( 4756): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a324 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 6
D/libc    (  365): [NET]res_nsend:resplen=93
D/libc    (  365): [NET]res_queryN: exit 3, ancount=3
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4756): [NET] getaddrinfo_proxy-, success
,I/global  ( 4756): call createSocket() return a new socket.
D/libc    ( 4756): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4756): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4756): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4756): [NET] getaddrinfo-,err=8
,D/PMS     (  988): acquireWL(442d89e0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4756 10027 null
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,I/HtcKeyguardAppUpdateMonitor( 1124): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1124): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1124): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1348): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "sms"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/ActivityManager(  988): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4973 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/Prism.ItemManager( 1282): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1282): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1282): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "smsto"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/Launcher( 1282): Deferring update until onResume
,D/Launcher( 1282): waitUntilResume // bindAppsUpdated
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "mms"
W/AccTypeManager( 1348): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1348): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,W/SystemReader( 1264): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "mmsto"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "sms"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "smsto"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
E/ExternalAccountType( 1348): Unsupported attribute readOnly
,I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "mms"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "mmsto"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,I/Babel   ( 4973): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4973): MmsConfig.loadMmsSettings
,W/dalvikvm( 4973): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4973): VFY: unable to resolve instance field 36
,W/dalvikvm( 4973): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4973): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC <<
I/ActivityManager(  988): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4996 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4973, uid=10111, userID:0
,W/Settings( 4973): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4973, uid=10111, userID:0
,I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4973, uid=10111, userID:0
,I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4973, uid=10111, userID:0
,I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4973, uid=10111, userID:0
,I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4973, uid=10111, userID:0
,D/MessageFrequencyProvider( 4996): onCreate
D/PMS     (  988): acquireWL(42da94a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4973 10111 null
,D/MmsCustomizationProvider( 4996): query uri: content://htc-mms-customization/mms-ua/ua_string
V/GetPrviateResource( 4996): GetPrviateResource
,V/GetPrviateResource( 4996): GetPrviateResource
,I/ActivityManager(  988): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/MmsCustomizationProvider( 4996): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1321): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1321): handle notify Blinkfeed plugin client changed
I/ActivityManager(  988): Resuming delayed broadcast
,I/IcingCorporaProvider( 2967): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Babel   ( 4973): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4973): MmsConfig.loadFromDatabase
I/ActivityManager(  988): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,E/Babel   ( 4973): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4973): MmsConfig.loadFromResources
,E/Babel   ( 4973): canonicalizeMccMnc: invalid mccmnc nullnull
,I/ProviderInstaller( 4973): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  988): acquireWL(443d2958): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 4973): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  988): releaseWL(443d2958): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/MessageCustFlag( 4996): sense_version=6.0
,D/BTAccessoryUtil( 4996): createReceiver
,D/BTAccessoryUtil( 4996): registerReceiver return intent = null
D/MessageCustFlag( 4996): sku_id=99
,W/SystemReader( 4996): Cannot find message_ambs_application_id, use default value instead
,D/Process (  988): killProcessQuiet, pid=4583
D/PMS     (  988): acquireWL(44052560): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): releaseWL(42da94a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  988): Killing 4583:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Messaging( 4996): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4996): networkCode: 
D/MessageCustFlag( 4996): sku_id=99
D/MmsConfig( 4996): SIE smsPri: null
D/MmsConfig( 4996): networkCode: 
D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/HtcTelephonyCapability( 4996): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4996): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4996): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4996): Cannot find qct_8960_interface, use default value instead
,W/PackageManager(  988): Unable to load service info ResolveInfo{42d201b0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  988): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  988): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  988): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  988): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  988): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  988): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  988): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  988): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  988): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  988): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  988): Recipient 4583
I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  988): releaseWL(44052560): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  988): Resuming delayed broadcast
,D/PMS     (  988): acquireWL(43061538): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  988): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/dalvikvm-heap( 4263): Grow heap (frag case) to 15.218MB for 1821008-byte allocation
D/PMS     (  988): acquireWL(44382c98): PARTIAL_WAKE_LOCK  AsyncService 0x1 4263 10160 null
,I/dalvikvm-heap( 4263): Grow heap (frag case) to 16.949MB for 1821008-byte allocation
D/PMS     (  988): releaseWL(44382c98): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  988): releaseWL(43061538): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  988): Resuming delayed broadcast
,I/ActivityManager(  988): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  988): acquireWL(431499d0): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): releaseWL(431499d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  988): Resuming delayed broadcast
,I/ActivityManager(  988): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  988): acquireWL(4311d0a8): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/RemoteDisplayProvider(  988): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  988): start
,I/GCoreNlp( 1232): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PMS     (  988): releaseWL(4311d0a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  988): Resuming delayed broadcast
,D/PMS     (  988): acquireWL(42cf5e20): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  988): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/LocationProviderProxy(  988): applying state to connected service
D/PMS     (  988): acquireWL(447de048): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): releaseWL(447de048): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  988): getActiveNetworkInfo called by com.facebook.katana (4756/10027)
,D/PMS     (  988): releaseWL(42cf5e20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  988): applying state to connected service
I/ActivityManager(  988): Resuming delayed broadcast
D/PMS     (  988): acquireWL(447b7760): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): acquireWL(44785a30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): releaseWL(447b7760): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): acquireWL(4477c598): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  988): releaseWL(44785a30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): releaseWL(4477c598): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(44774608): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): releaseWL(44774608): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  988): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2187): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2187): Null package name or gms related package.  Ignoreing.
D/PMS     (  988): acquireWL(44773080): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2187): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2967): UpdateCorporaTask done [took 482 ms] updated apps [took 482 ms] 
I/ActivityManager(  988): Resuming delayed broadcast
,D/CaptivePortalTracker(  988): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  988): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  988): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1282): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1282): loadItems() com.htc.launcher.pageview.WidgetManager@42227c30 +
,I/Prism.WidgetManager( 1282): onLoadItems() +
,D/AutoSetting( 1525): service - handleMessage() stop self
,I/Icing   ( 2187): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/AutoSetting( 1525): service - onDestroy() END
,D/AutoSetting( 1525): service - handleMessage() quit looper
,D/Process (  988): killProcessQuiet, pid=4600
,I/ActivityManager(  988): Killing 4600:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  988): Recipient 4600
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  988): Client connection lost with reason: 4
,I/Icing   ( 2187): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  988): releaseWL(44773080): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1282): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1282): onLoadItems() -
,I/Prism.ItemManager( 1282): loadItems() com.htc.launcher.pageview.WidgetManager@42227c30 -
,D/PhoneApp( 1248): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1248): -- N1 =0
,D/PhoneApp( 1248): -- N2 =0
,D/PhoneApp( 1248): -- N3 =0
,D/Messaging( 4996): mNeedToUpdateDate2 start
,D/MmsConfig( 4996): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4996): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4996): 
D/MmsAsyncWorkHandler( 4996): HM tk = 20001
D/ReportIndicatorCache( 4996): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4996): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@421a1608
,I/Messaging( 4996): mccmnc> 
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4996): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4996): [DraftCache/1] refresh
,D/MmsConfig( 4996): networkCode: 
,D/Messaging( 4996): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/PhoneStorageUtil( 4996): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4996): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4996): createReceiver
,D/MessageCustFlag( 4996): sense_version=6.0
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Jerry   ( 4996): start to preload cursor >>>>>>>
,D/Messaging( 4996): mNeedToUpdateDate2: false
,D/TelephUtils( 1248): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
,V/MmsProvider( 1248): Update uri=content://mms, match=0
V/MmsProvider( 1248): selection=st=129 AND m_type!=134
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1248): sku_id=99
,D/Messaging( 4996): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4996): TransactionService is going to be woken up.
,V/TransactionService( 4996): 1-Creating TransactionService
,D/DraftCache( 4996): [DraftCache/496] rebuildCache
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4996): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MmsSmsV2Provider( 1248):  phoneType = -1
V/TransactionService( 4996): onStartCommand: 1
,D/MmsSystemEventReceiver( 4996): unRegisterForConnectionStateChanges
V/TransactionService( 4996): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4996): Loading previous transactions.
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
,D/Jerry   ( 1248): URI_DRAFT
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1248): device_type: 1
D/Messaging( 4996): ViewCache CreatePreload
,D/Messaging( 4996): ViewCache CreatePreloadOnlyMultipleOpsList
,D/DraftCache( 4996): hasDraft() = false mNeedNotifyChange = true
,D/TransactionService( 4996): Force set service start id to 1
V/TransactionService( 4996): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4996): unRegisterForConnectionStateChanges
D/DraftCache( 4996): [DraftCache/496] rebuildCache time: 3
D/TransactionService( 4996): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4996): Destroying TransactionService
,D/MmsAsyncWorkHandler( 4996): 
D/MmsAsyncWorkHandler( 4996): HM tk = 20002
,D/Cust_MMSMS( 4996): _has_set_default_values_2=true
,V/TransactionService( 4996): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1248): sku_id=99
,D/MsgPreferenceUtils( 4996): def_index: 0
,D/MsgPreferenceUtils( 4996): globalIndex = 1
D/MsgPreferenceUtils( 4996): phone state: true
D/MsgPreferenceUtils( 4996): sd state: false
,D/MsgPreferenceUtils( 4996): vIndex = 0
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1248): sku_id=99
,I/global  ( 4756): I/O error closing connection
I/global  ( 4756): java.net.SocketException: Socket is closed
I/global  ( 4756): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4756): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4756): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4756): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4756): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4756): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4756): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4756): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4756): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4756): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4756): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4756): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4756): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4756): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4756): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4756): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4756): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4756): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4756): Removing a connection that never existed!
D/PMS     (  988): releaseWL(442d89e0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  988): Waited long enough for: ServiceRecord{442e1bc0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4973): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  988): killProcessQuiet, pid=4123
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  988): Killing 4123:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  988): Recipient 4123
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  988): acquireWL(4431c850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 988 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  988): sending alarm PendingIntent{44234918: PendingIntentRecord{4408f608 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=128595, Int=0
,D/PMS     (  988): releaseWL(4431c850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(44742578): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=4 [67][3][0]
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/PMS     (  988): acquireWL(42cf1280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): releaseWL(42cf1280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): releaseWL(44742578): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(4278a9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/PMS     (  988): releaseWL(4278a9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(4249beb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/PMS     (  988): acquireWL(429b6c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(42cb8e70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1232): Vacuum at: now=1452509458005 tag=VacuumService
,D/PMS     (  988): releaseWL(4249beb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): releaseWL(429b6c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(43de3f78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/PMS     (  988): releaseWL(42cb8e70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): releaseWL(43de3f78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(4385b978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/PMS     (  988): releaseWL(4385b978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(44124510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/PMS     (  988): releaseWL(44124510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  988): acquireWL(443dd468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 988 1000 WorkSource{1000}
,V/AlarmManager(  988): sending alarm PendingIntent{425c2a78: PendingIntentRecord{4257d2d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=130868, Int=0
,I/IntentController( 1124): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  988): releaseWL(443dd468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  988): acquireWL(4322de70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  988): n_update end
,D/PMS     (  988): releaseWL(4322de70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  988): BroadcastReceiver::onReceive-
,I/IntentController( 1124): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  988): updateBatteryInfo
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1124): closing low battery warning: level=100
D/PowerUI ( 1124): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1124): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=20 entropy=8
D/wpa_supplicant( 1167): Add randomness: count=21 entropy=9
D/wpa_supplicant( 1167): Add randomness: count=22 entropy=10
D/wpa_supplicant( 1167): Add randomness: count=23 entropy=11
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 ,last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=24 entropy=12
D/wpa_supplicant( 1167): Add randomness: count=25 entropy=13
D/wpa_supplicant( 1167): Add randomness: count=26 entropy=14
D/wpa_supplicant( 1167): Add randomness: count=27 entropy=15
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  988): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (489) for get BSS: id=0,
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-47
I/wpa_supplicant( 1167): tsf=0000000132722273
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====,
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000115589139
,I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
,I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000132722310
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000132722323
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  988): getDiscoveryDongleList
W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 132722273, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 115589139, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 132722310, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 132722323, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): add 4 to mScanResults
,V/ScoreHelper(  988): Only print Top 10 in ApScanList
,V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  988):  + computeScore(NG700): 1
,D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (4) end of scan result ==
D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/WifiManager( 1232): getScanResults enter 
D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (4) end of scan result ==
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1321): service - mHandler: update timezone
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  988): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1525): service - onCreate()
D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  988): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1525): service - mHandler: update timezone
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  988): batLight: Full, plugged
V/LightsService(  988): setLight #8: color=#c8c800
D/qdlights(  988): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  988): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  988): setLight #8: color=#c800
D/qdlights(  988): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  988): [LedInfo] has indicator attribute
D/qdlights(  988): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  988): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1525): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1525): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1124): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1124): release indeterminate drawable android.widget.OnDemandProgressBar{422d7d80 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1124): com.htc.htclocationservice 2 8 2 11
,D/PMS     (  988): acquireWL(447b99e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 988 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  988): sending alarm PendingIntent{42d315b8: PendingIntentRecord{43e31ba0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144375, Int=0
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
,D/PMS     (  988): releaseWL(447b99e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(44064558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=20 [5][1][0]
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1321): service - handleMessage() stop self
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1321): service - handleMessage() quit looper
,D/AutoSetting( 1321): service - onDestroy() END
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/PMS     (  988): acquireWL(442d39f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): releaseWL(442d39f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(42de78f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): releaseWL(44064558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(42ea4550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/PMS     (  988): releaseWL(42ea4550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (1232/10029)
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (1232/10029)
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1232): Scheduling Phenotype for one-off execution 7190 seconds from now (1452509474239)
,D/GetConfigurationSnapshotOperation( 1232): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1232): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1232): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1232): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1232): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1232): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1232): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  988): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (1232/10029)
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (1232/10029)
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/libc    ( 1232): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1232): [NET] getaddrinfo-,err=8
D/libc    ( 1232): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1232): [NET] getaddrinfo-, 1
,D/libc    ( 1232): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e5be +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1232): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1232): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1232): [NET] getaddrinfo-,err=8
D/libc    ( 1232): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1232): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  988): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (1232/10029)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL,
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.google.android.gms (1232/10029)
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/PMS     (  988): releaseWL(42de78f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(440e6420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349,
,D/GpsLocationProvider(  988): ALARM_XTRA_TIMEOUT
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
D/PMS     (  988): acquireWL(4477c358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 988 1000 WorkSource{1000}
V/AlarmManager(  988): sending alarm PendingIntent{42a64480: PendingIntentRecord{4265d838 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=146280, Int=0
D/PMS     (  988): acquireWL(43b406f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 988 1000 null
D/GpsLocationProvider(  988): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  988): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  988): releaseWL(4477c358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  988): releaseWL(440e6420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  988): acquireWL(440d6b78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (1376/10029)
D/WifiNative-wlan0(  988): doString: SIGNAL_POLL
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/libc    (  988): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  988): [NET] getaddrinfo-,err=8
D/libc    (  988): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  988): [NET] getaddrinfo-, 1
D/libc    (  988): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a75d +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/PMS     (  988): releaseWL(440d6b78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  988): killProcessQuiet, pid=4627
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  988): Killing 4627:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  988): Recipient 4627
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  988): [NET] getaddrinfo_proxy-, success
,I/global  (  988): call createSocket() return a new socket.
D/libc    (  988): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  988): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  988): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  988): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  988): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  988):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  988): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=28 entropy=16
D/wpa_supplicant( 1167): Add randomness: count=29 entropy=17
D/wpa_supplicant( 1167): Add randomness: count=30 entropy=18
D/wpa_supplicant( 1167): Add randomness: count=31 entropy=19
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=32 entropy=20
D/wpa_supplicant( 1167): Add randomness: count=33 entropy=21
D/wpa_supplicant( 1167): Add randomness: count=34 entropy=22
D/wpa_supplicant( 1167): Add randomness: count=35 entropy=23
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  988): doString: LIST_DONGLES
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  988): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (489) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-47
I/wpa_supplicant( 1167): tsf=0000000149832445
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====,
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000115589139
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000149832484
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
,I/wpa_supplicant( 1167): tsf=0000000132722323
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 149832445, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 115589139, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 149832484, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 132722323, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): add 4 to mScanResults
,V/ScoreHelper(  988): Only print Top 10 in ApScanList
,V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  988):  + computeScore(NG700): 1
,D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (4) end of scan result ==
D/WifiManager( 1232): getScanResults enter 
,D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (4) end of scan result ==
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  988): releaseWL(43b406f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  988): Waited long enough for: ServiceRecord{43b47890 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1167): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=36 entropy=24
D/wpa_supplicant( 1167): Add randomness: count=37 entropy=25
D/wpa_supplicant( 1167): Add randomness: count=38 entropy=26
D/wpa_supplicant( 1167): Add randomness: count=39 entropy=27
D/wpa_supplicant( 1167): Add randomness: count=40 entropy=28
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplican,t( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1167): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=41 entropy=29
D/wpa_supplicant( 1167): Add randomness: count=42 entropy=30
D/wpa_supplicant( 1167): Add randomness: count=43 entropy=31
D/wpa_supplicant( 1167): Add randomness: count=44 entropy=32
D/wpa_supplicant( 1167): Add randomness: count=45 entropy=33
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (636) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-46
I/wpa_supplicant( 1167): tsf=0000000167173801
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000115589139
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000167173840
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000167173851
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=4
I/wpa_supplicant( 1167): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000167173861
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
,I/wpa_supplicant( 1167): ssid=UPC4688432
I/wpa_supplicant( 1167): ####
D/WifiP2pService(  988): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  988): getDiscoveryDongleList,
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 167173801, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 115589139, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 167173840, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 167173851, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 167173861, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): add 5 to mScanResults
,V/ScoreHelper(  988): Only print Top 10 in ApScanList
,V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  988):  + computeScore(NG700): 1
D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (5) end of scan result ==
D/WifiManager( 1232): getScanResults enter 
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (5) end of scan result ==
,D/WirelessDisplayService(  988): getDiscoveryDongleList
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1525): service - handleMessage() stop self
,D/AutoSetting( 1525): service - onDestroy() END
,D/AutoSetting( 1525): service - handleMessage() quit looper
,D/Process (  988): killProcessQuiet, pid=4641
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  988): Killing 4641:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  988): Recipient 4641
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  988): acquireWL(436d3008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  988): n_update end
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  988): BroadcastReceiver::onReceive-
,I/IntentController( 1124): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1124): closing low battery warning: level=100
D/PowerUI ( 1124): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  988): updateBatteryInfo
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
D/PMS     (  988): releaseWL(436d3008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  988): >> updateStatus
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1124): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1167): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=46 entropy=34
D/wpa_supplicant( 1167): Add randomness: count=47 entropy=35
D/wpa_supplicant( 1167): Add randomness: count=48 entropy=36
D/wpa_supplicant( 1167): Add randomness: count=49 entropy=37
D/wpa_supplicant( 1167): Add randomness: count=50 entropy=38
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): ,send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1167): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=51 entropy=39
D/wpa_supplicant( 1167): Add randomness: count=52 entropy=40
D/wpa_supplicant( 1167): Add randomness: count=53 entropy=41
D/wpa_supplicant( 1167): Add randomness: count=54 entropy=42
D/wpa_supplicant( 1167): Add randomness: count=55 entropy=43
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  988): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (636) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-46
I/wpa_supplicant( 1167): tsf=0000000184474591
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000115589139
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2,
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000184474629
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000184474639
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=4
I/wpa_supplicant( 1167): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000184474648
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC4688432
I/wpa_supplicant( 1167): ####
W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 184474591, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 115589139, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 184474629, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 184474639, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 184474648, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): add 5 to mScanResults
V/ScoreHelper(  988): Only print Top 10 in ApScanList
V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  988):  + computeScore(NG700): 1
D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (5) end of scan result ==
,D/WifiManager( 1232): getScanResults enter 
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (5) end of scan result ==
,D/WirelessDisplayService(  988): getDiscoveryDongleList
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000),
,D/PMS     (  988): acquireWL(44765df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 988 1000 WorkSource{1000}
,V/AlarmManager(  988): sending alarm PendingIntent{425c2a78: PendingIntentRecord{4257d2d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=190869, Int=0
,I/IntentController( 1124): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  988): releaseWL(44765df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  988): acquireWL(430905a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  988): n_update end
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
I/IntentController( 1124): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/PMS     (  988): releaseWL(430905a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  988): updateBatteryInfo
D/PowerUI ( 1124): closing low battery warning: level=100
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1124): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1124): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1167): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=56 entropy=44
D/wpa_supplicant( 1167): Add randomness: count=57 entropy=45
D/wpa_supplicant( 1167): Add randomness: count=58 entropy=46
D/wpa_supplicant( 1167): Add randomness: count=59 entropy=47
D/wpa_supplicant( 1167): Add randomness: count=60 entropy=48
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
,I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
,I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
,I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1167): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=61 entropy=49
D/wpa_supplicant( 1167): Add randomness: count=62 entropy=50
D/wpa_supplicant( 1167): Add randomness: count=63 entropy=51
D/wpa_supplicant( 1167): Add randomness: count=64 entropy=52
D/wpa_supplicant( 1167): Add randomness: count=65 entropy=53
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  988): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  988): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (636) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-46
I/wpa_supplicant( 1167): tsf=0000000201823674
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000115589139
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000201823712
,I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000201823722
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=4
I/wpa_supplicant( 1167): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000201823732
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC4688432
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  988): getDiscoveryDongleList
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 201823674, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 115589139, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 201823712, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 201823722, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  988): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 201823732, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): add 5 to mScanResults
,V/ScoreHelper(  988): Only print Top 10 in ApScanList
V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  988):  + computeScore(NG700): 1
D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (5) end of scan result ==
,D/WifiManager( 1232): getScanResults enter 
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (5) end of scan result ==
,D/WirelessDisplayService(  988): getDiscoveryDongleList
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,I/ClearcutLoggerApiImpl( 1376): disconnect managed GoogleApiClient
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=66 entropy=54
D/wpa_supplicant( 1167): Add randomness: count=67 entropy=55
D/wpa_supplicant( 1167): Add randomness: count=68 entropy=56
D/wpa_supplicant( 1167): Add randomness: count=69 entropy=57
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=70 entropy=58
D/wpa_supplicant( 1167): Add randomness: count=71 entropy=59
D/wpa_supplicant( 1167): Add randomness: count=72 entropy=60
D/wpa_supplicant( 1167): Add randomness: count=73 entropy=61
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (636) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-46
I/wpa_supplicant( 1167): tsf=0000000219214050
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000115589139
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000219214089
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000219214100
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=4
I/wpa_supplicant( 1167): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000201823732
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC4688432
I/wpa_supplicant( 1167): ####
D/WifiP2pService(  988): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  988): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 219214050, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 115589139, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 219214089, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 219214100, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 201823732, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): add 5 to mScanResults
,V/ScoreHelper(  988): Only print Top 10 in ApScanList
,V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  988):  + computeScore(NG700): 1
,D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1232): getScanResults enter 
D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (5) end of scan result ==
D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (5) end of scan result ==
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000),
D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/PMS     (  988): acquireWL(43a9ae38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 988 1000 WorkSource{10027}
,V/AlarmManager(  988): sending alarm PendingIntent{42ab7920: PendingIntentRecord{44009540 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226887, Int=0
,I/ActivityManager(  988): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5079 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  988): sending alarm PendingIntent{42c96b98: PendingIntentRecord{42befb00 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452509545892, Int=10800000
,D/PMS     (  988): releaseWL(43a9ae38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  988): getActiveNetworkInfo called by com.htc.aurora (5079/10049)
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028444
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360028917
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029264
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029273
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029281
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360029284
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030790
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360030826
W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360033349
,W/AlarmManager(  988): Converted elapesd time is over 1 year! when = 315360034764
,D/Process (  988): killProcessQuiet, pid=4344
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  988): Killing 4344:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  988): Recipient 4344
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  988): acquireWL(43f7c0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  988): n_update end
,D/PMS     (  988): releaseWL(43f7c0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1124): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  988): updateBatteryInfo
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
D/PowerUI ( 1124): closing low battery warning: level=100
D/PowerUI ( 1124): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  988): acquireWL(441fa340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 988 1000 WorkSource{10027}
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  988): << updateStatus
,V/AlarmManager(  988): sending alarm PendingIntent{42539730: PendingIntentRecord{44009540 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=233644, Int=0
,D/PMS     (  988): releaseWL(441fa340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/BatteryController( 1124): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=74 entropy=62
D/wpa_supplicant( 1167): Add randomness: count=75 entropy=63
D/wpa_supplicant( 1167): Add randomness: count=76 entropy=64
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=77 entropy=65
D/wpa_supplicant( 1167): Add randomness: count=78 entropy=66
D/wpa_supplicant( 1167): Add randomness: count=79 entropy=67
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  988): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (489) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-46
I/wpa_supplicant( 1167): tsf=0000000236553890
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000115589139
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000236553916
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000236553927
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 236553890, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 115589139, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 236553916, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 236553927, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): add 4 to mScanResults
,V/ScoreHelper(  988): Only print Top 10 in ApScanList
,V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  988):  + computeScore(NG700): 1
,D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiManager( 1232): getScanResults enter 
D/WifiStateMachine(  988): == (4) end of scan result ==
,D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (4) end of scan result ==
,D/WirelessDisplayService(  988): getDiscoveryDongleList,
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  988): acquireWL(43be6ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 988 1000 WorkSource{1000}
,V/AlarmManager(  988): sending alarm PendingIntent{425c2a78: PendingIntentRecord{4257d2d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=250869, Int=0
,I/IntentController( 1124): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  988): releaseWL(43be6ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  988): acquireWL(440e6b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  988): n_update end
,D/PMS     (  988): releaseWL(440e6b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  988): updateBatteryInfo
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
,I/IntentController( 1124): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1124): closing low battery warning: level=100
D/PowerUI ( 1124): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1124): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=80 entropy=68
D/wpa_supplicant( 1167): Add randomness: count=81 entropy=69
D/wpa_supplicant( 1167): Add randomness: count=82 entropy=70
D/wpa_supplicant( 1167): Add randomness: count=83 entropy=71
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=84 entropy=72
D/wpa_supplicant( 1167): Add randomness: count=85 entropy=73
D/wpa_supplicant( 1167): Add randomness: count=86 entropy=74
D/wpa_supplicant( 1167): Add randomness: count=87 entropy=75
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
,I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  988): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (489) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-46
I/wpa_supplicant( 1167): tsf=0000000253894238
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000253894264
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000253894276
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
,I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000253894286
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 253894238, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 253894264, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 253894276, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 253894286, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): add 4 to mScanResults
,V/ScoreHelper(  988): Only print Top 10 in ApScanList
V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  988):  + computeScore(NG700): 1
D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiManager( 1232): getScanResults enter 
D/WifiStateMachine(  988): == (4) end of scan result ==
D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (4) end of scan result ==
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=88 entropy=76
D/wpa_supplicant( 1167): Add randomness: count=89 entropy=77
D/wpa_supplicant( 1167): Add randomness: count=90 entropy=78
D/wpa_supplicant( 1167): Add randomness: count=91 entropy=79
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=92 entropy=80
D/wpa_supplicant( 1167): Add randomness: count=93 entropy=81
D/wpa_supplicant( 1167): Add randomness: count=94 entropy=82
D/wpa_supplicant( 1167): Add randomness: count=95 entropy=83
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  988): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (489) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-46
I/wpa_supplicant( 1167): tsf=0000000271123507
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000271123535
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000271123545
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000271123558
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 271123507, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 271123535, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 271123545, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 271123558, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): add 4 to mScanResults
V/ScoreHelper(  988): Only print Top 10 in ApScanList
V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  988):  + computeScore(NG700): 1
D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (4) end of scan result ==
,D/WifiManager( 1232): getScanResults enter 
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (4) end of scan result ==
,D/WirelessDisplayService(  988): getDiscoveryDongleList
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=96 entropy=84
D/wpa_supplicant( 1167): Add randomness: count=97 entropy=85
D/wpa_supplicant( 1167): Add randomness: count=98 entropy=86
D/wpa_supplicant( 1167): Add randomness: count=99 entropy=87
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=100 entropy=88
D/wpa_supplicant( 1167): Add randomness: count=101 entropy=89
D/wpa_supplicant( 1167): Add randomness: count=102 entropy=90
D/wpa_supplicant( 1167): Add randomness: count=103 entropy=91
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  988): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (489) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-46
I/wpa_supplicant( 1167): tsf=0000000288424047
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000288424074
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000288424085
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000288424095
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  988): getDiscoveryDongleList
D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  988): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 288424047, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 288424074, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 288424085, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 288424095, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): add 4 to mScanResults
,V/ScoreHelper(  988): Only print Top 10 in ApScanList
V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  988):  + computeScore(NG700): 1
D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiManager( 1232): getScanResults enter 
,D/WifiStateMachine(  988): == (4) end of scan result ==
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (4) end of scan result ==
,D/WirelessDisplayService(  988): getDiscoveryDongleList
,D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,D/PMS     (  988): acquireWL(43999400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  988): n_update end
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  988): BroadcastReceiver::onReceive-
,I/IntentController( 1124): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  988): updateBatteryInfo
D/PMS     (  988): releaseWL(43999400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1124): closing low battery warning: level=100
D/PowerUI ( 1124): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1124): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=104 entropy=92
D/wpa_supplicant( 1167): Add randomness: count=105 entropy=93
D/wpa_supplicant( 1167): Add randomness: count=106 entropy=94
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
,I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
,D/wpa_supplicant( 1167): Add randomness: count=107 entropy=95
D/wpa_supplicant( 1167): Add randomness: count=108 entropy=96
D/wpa_supplicant( 1167): Add randomness: count=109 entropy=97
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  988): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (489) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-46
I/wpa_supplicant( 1167): tsf=0000000305764017
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000288424074
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000305764044
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000305764055
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  988): getDiscoveryDongleList
D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  988): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 305764017, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 288424074, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 305764044, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 305764055, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): add 4 to mScanResults
V/ScoreHelper(  988): Only print Top 10 in ApScanList
V/ScoreHelper(  988):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  988):  + computeScore(NG700): 1
D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiManager( 1232): getScanResults enter 
D/WifiStateMachine(  988): == (4) end of scan result ==
D/WifiStateMachine(  988): == begin of scan result ==
,D/WifiStateMachine(  988): == (4) end of scan result ==
,D/WirelessDisplayService(  988): getDiscoveryDongleList
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,D/PMS     (  988): acquireWL(43b97830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 988 1000 WorkSource{1000}
,V/AlarmManager(  988): sending alarm PendingIntent{425c2a78: PendingIntentRecord{4257d2d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=310868, Int=0
,I/IntentController( 1124): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  988): releaseWL(43b97830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  988): acquireWL(42d44c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  988): n_update end
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1124): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1124): closing low battery warning: level=100
D/PowerUI ( 1124): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  988): releaseWL(42d44c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1124): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=110 entropy=98
D/wpa_supplicant( 1167): Add randomness: count=111 entropy=99
D/wpa_supplicant( 1167): Add randomness: count=112 entropy=100
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=113 entropy=101
D/wpa_supplicant( 1167): Add randomness: count=114 entropy=102
D/wpa_supplicant( 1167): Add randomness: count=115 entropy=103
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1167): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  988): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  988): doString: LIST_DONGLES
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  988): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  988): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  988): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-46
I/wpa_supplicant( 1167): tsf=0000000305764017
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000323113899
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700,
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2452
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000323113912
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  988): getDiscoveryDongleList
D/WifiStateMachine(  988): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  988): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 305764017, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 323113899, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  988): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 323113912, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  988): add 3 to mScanResults
D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
,V/ScoreHelper(  988): Only print Top 10 in ApScanList
V/ScoreHelper(  988):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  988):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  988):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  988): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  988):  + computeScore(NG700): 1
D/WifiStateMachine(  988): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (3) end of scan result ==
D/WifiManager( 1232): getScanResults enter 
,D/WirelessDisplayService(  988): getDiscoveryDongleList
D/WifiNotificationController(  988): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  988): getActiveNetworkInfo called by  (988/1000)
D/WifiStateMachine(  988): == begin of scan result ==
D/WifiStateMachine(  988): == (3) end of scan result ==
,I/jxcore-log( 4690): --= Surplus to requirements =--
I/jxcore-log( 4690): 
I/jxcore-log( 4690): ****TEST TOOK:  ms ****
I/jxcore-log( 4690): 
,I/jxcore-log( 4690): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4690): 
,E/cutils-trace( 5104): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 5104): ====startRecUseTime====
D/htc.customization.log.level( 5104):  is 
,W/CustomizationLogLevel( 5104): Level value is invalid, use default level 2
,D/CustomizationManager( 5104):  Read ACC file spent 0.107 (s)
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 5104): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5104): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5104): Parsing tag category name = system
I/CustomizationCIDLoader( 5104): Parsing tag category name = application
I/CustomizationCIDLoader( 5104): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5104): Parsing tag category name = AutomotiveHome,
,I/CustomizationCIDLoader( 5104): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5104): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5104): Parsing tag category name = Settings
,D/CustomizationManager( 5104):  Read CID file spent 0.155 (s)
,D/CustomizationManager( 5104):  All configurations done spent 0.155 (s)
,W/HtcNativeFlag( 5104): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5104): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5104): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 5104): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  988): deletePackageAsUser: pkg=com.test.thalitest, pid=5104, uid=2000 user=0
,I/ActivityManager(  988): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,I/ActivityManager(  988): Killing 4690:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
D/Process (  988): killProcessQuiet, pid=4690
D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  988): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  988):   Force finishing activity ActivityRecord{447d0630 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  988): Copying FileAsset 0x63319d98 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  988): channel '4427ad88 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  988): channel '4427ad88 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  988): Attempted to unregister already unregistered input channel '4427ad88 com.test.thalitest.MainActivity (s)'
I/WindowManager(  988): WINDOW DIED Window{4427ad88 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  988): Client connection lost with reason: 4
W/WindowManager(  988): Failed looking up window
W/WindowManager(  988): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@4405c030 does not exist
W/WindowManager(  988): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  988): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  988): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  988): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  988): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  988): WIN DEATH: null
,W/Binder  ( 1218): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1218): java.lang.NullPointerException
W/Binder  ( 1218): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1218): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1218): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1218): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  988): Got RemoteException sending setActive(false) notification to pid 4690 uid 10389
W/PackageSettings(  988): Skipping PackageSetting{428a86b8 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  988): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1124): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1124): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1124): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/GeofencerStateMachine( 1232): Ignoring removeGeofence because network location is disabled.
D/PMS     (  988): acquireWL(43e08e20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1232 10029 WorkSource{10029 com.google.android.gms}
,D/AccTypeManager( 1348): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  988): releaseWL(43e08e20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/VoicemailCleanupService( 1294): Cleaning up data for package: com.test.thalitest
,W/SystemReader( 1264): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1282): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1282): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/[PluginManager]RegisterService( 1321): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/Launcher( 1282): Deferring update until onResume
D/Launcher( 1282): waitUntilResume // bindAppsRemoved
,D/Prism.PackageStateRece_( 1282): action: android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1321): handle notify Blinkfeed plugin client changed
,W/SQLiteConnectionPool( 2187): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1348): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1348): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "sms"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/InputMethodManagerService(  988): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "smsto"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/IcingCorporaProvider( 2967): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "mms"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "mmsto"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/ActivityManager(  988): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5119 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/ExternalAccountType( 1348): Unsupported attribute readOnly
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "sms"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "smsto"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "mms"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  988):   Scheme: "mmsto"
I/PackageManager(  988): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  988): acquireWL(423e8560): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2967): UpdateCorporaTask done [took 439 ms] updated apps [took 439 ms] 
,E/SQLiteDatabase( 5119): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5119): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5119): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5119): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5119): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5119): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5119): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5119): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5119): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5119): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5119): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5119): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5119): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5119): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5119): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5119): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5119): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5119): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5119): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5119): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5119): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5119): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5119): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5119): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5119): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5119): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5119): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5119): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 5119): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5119): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5119): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5119): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5119): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5119): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5119): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5119): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5119): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5119): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5119): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5119): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5119): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5119): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5119): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5119): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5119): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5119): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5119): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5119): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5119): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5119): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5119): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5119): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5119): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5119): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5119): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5119): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 5119): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 5119): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5119): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5119): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5119): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5119): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5119): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5119): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5119): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5119): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 5119): threadid=11: thread exiting with uncaught exception (group=0x41d64e30)
,E/ActivityManager(  988): App crashed! Process: com.google.android.apps.docs,
E/AndroidRuntime( 5119): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5119): Process: com.google.android.apps.docs, PID: 5119
E/AndroidRuntime( 5119): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5119): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5119): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5119): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5119): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5119): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5119): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5119): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5119): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  988): Can't write: system_app_crash
E/DropBoxManagerService(  988): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  988): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  988): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  988): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  988): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  988): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  988): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  988): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  988): 	... 5 more
,D/Process ( 5119): killProcess, pid=5119
,D/Process ( 5119): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  988): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5139 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  988): Recipient 5119
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  988): killProcessQuiet, pid=4735
,D/Process (  988): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  988): Killing 4735:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/ActivityManager(  988): Process com.google.android.apps.docs (pid 5119) has died.
,I/ActivityManager(  988): Recipient 4735
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 5139): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  988): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5152 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 5139): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5139): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5139): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5139): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5139): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5139): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5139): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5139): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5139): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5139): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5139): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5139): threadid=10: thread exiting with uncaught exception (group=0x41d64e30)
E/AndroidRuntime( 5139): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5139): Process: com.android.keychain, PID: 5139
E/AndroidRuntime( 5139): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5139): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5139): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5139): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5139): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5139): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5139): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5139): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5139): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5139): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  988): App crashed! Process: com.android.keychain
D/ErrorReport(  988): HtcErrorReportManager Begin---add error logs to dropbox
,I/Prism.ItemManager( 1282): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1282): loadItems() com.htc.launcher.pageview.WidgetManager@42227c30 +
,I/Prism.WidgetManager( 1282): onLoadItems() +
,D/AppTag  ( 5152): getInstance(Context context)
,D/Process ( 5139): killProcess, pid=5139
,D/Process ( 5139): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/AppTag  ( 5152): getInstance(Context context)
,D/AppTag  ( 5152): onCreate()
E/ErrorReport(  988): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  988): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452509660001.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  988): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  988): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  988): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  988): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  988): 	at libcore.io.Posix.open(Native Method)
,E/ErrorReport(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  988): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  988): 	... 4 more
I/ActivityManager(  988): Recipient 5139
I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  988): Process com.android.keychain (pid 5139) has died.
,W/ActivityManager(  988): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/PMS     (  988): acquireWL(4384f130): PARTIAL_WAKE_LOCK  AsyncService 0x1 4263 10160 null
,D/PMS     (  988): releaseWL(4384f130): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4287): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/PackageBroadcastService( 2187): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2187): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2187): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2187): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2187): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2187): Module APK com.google.android.play.games already loaded
I/ActivityManager(  988): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/LocationSettingsChecker( 2187): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 2187): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 2187): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2187): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65a8dc20
,E/SQLiteDBG( 2187): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca41950
,W/dalvikvm( 2187): threadid=46: thread exiting with uncaught exception (group=0x41d64e30)
,E/DriveAsyncService( 2187): disk I/O error (code 3850)
E/DriveAsyncService( 2187): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2187): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2187): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2187): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2187): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2187): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2187): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2187): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2187): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2187): 	at java.lang.Thread.run(Thread.java:864)
,W/PackageManager(  988): Unable to load service info ResolveInfo{4487fbc8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  988): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  988): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  988): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  988): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  988): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  988): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  988): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  988): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  988): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  988): 	at dalvik.system.NativeStart.main(Native Method)
,E/AndroidRuntime( 2187): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2187): Process: com.google.android.gms, PID: 2187
E/AndroidRuntime( 2187): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2187): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2187): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2187): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2187): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2187): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2187): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2187): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2187): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2187): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2187): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2187): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2187): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  988): App crashed! Process: com.google.android.gms
,E/DropBoxManagerService(  988): Can't write: system_app_crash
E/DropBoxManagerService(  988): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  988): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  988): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  988): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  988): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  988): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  988): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  988): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  988): 	... 5 more
,E/SQLiteDatabase( 2187): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2187): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2187): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2187): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2187): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2187): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2187): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2187): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2187): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Process ( 2187): killProcess, pid=2187
,E/SQLiteOpenHelper( 2187): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2187): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2187): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2187): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2187): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2187): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2187): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2187): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2187): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Process ( 2187): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/ActivityManager(  988): Recipient 2187
,I/DisplayManagerService(  988): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  988): Process com.google.android.gms (pid 2187) has died.
D/PMS     (  988): handleWLDeath(423e8560): PARTIAL_WAKE_LOCK  Icing 0x1
,D/WifiService(  988): Client connection lost with reason: 4
,W/ActivityManager(  988): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  988): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
,W/ActivityManager(  988): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,W/ActivityManager(  988): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
,I/ActivityManager(  988): Resuming delayed broadcast
,W/ActivityManager(  988): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  988): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
W/ActivityManager(  988): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
,W/ActivityManager(  988): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 21000ms
,E/SQLiteLog( 1376): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1376): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5ca47290
,W/dalvikvm( 1376): threadid=1: thread exiting with uncaught exception (group=0x41d64e30)
,E/ActivityManager(  988): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1376): FATAL EXCEPTION: main
E/AndroidRuntime( 1376): Process: com.google.process.gapps, PID: 1376
E/AndroidRuntime( 1376): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1376): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1376): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1376): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1376): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1376): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1376): 	... 10 more
,D/Process ( 1376): killProcess, pid=1376
,D/Process ( 1376): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  988): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5184 uid=10098 gids={50098, 3003, 5012}
,E/DropBoxManagerService(  988): Can't write: system_app_crash
E/DropBoxManagerService(  988): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  988): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  988): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  988): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  988): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  988): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  988): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  988): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  988): 	... 5 more

```
