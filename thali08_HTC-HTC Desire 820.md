#### Test 55431344e5dd625_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
,D/WIFI_ICON( 1118): WifiActivity: 0
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
--------- beginning of /dev/log/main
D/CustomizationManager( 4499): ====startRecUseTime====
D/htc.customization.log.level( 4499):  is 
W/CustomizationLogLevel( 4499): Level value is invalid, use default level 2
D/CustomizationManager( 4499):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4499): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4499): Parsing tag category name = system
I/CustomizationCIDLoader( 4499): Parsing tag category name = application
I/CustomizationCIDLoader( 4499): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4499): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4499): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4499): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4499): Parsing tag category name = Settings
D/CustomizationManager( 4499):  Read CID file spent 0.103 (s)
D/CustomizationManager( 4499):  All configurations done spent 0.103 (s)
W/HtcNativeFlag( 4499): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4499): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4499): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4499): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4499
D/PMS     (  906): acquireHCC(44004018): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(425a02e0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6f042210 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1131240496
D/PMS     (  906): acquireWL(437996d8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/FeedHostManager( 1270): [onPause]
E/cutils-trace( 4499): Error opening trace file: No such file or directory (2)
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c2c350
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4510 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4510): Copying FileAsset 0x5c70a810 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,V/WebViewChromiumFactoryProvider( 4510): Binding Chromium to main looper Looper (main, tid 1) {41a744e0}
I/LibraryLoader( 4510): Expected native library version number "",actual native library version number ""
I/chromium( 4510): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4510): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(43f72208): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  906): acquireWL(43bf5288): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@435ca9f0:true
,D/BluetoothAdapter( 4510): 1101569816: getState(). Returning 12
D/PMS     (  906): releaseWL(43f72208): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4510): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4510): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4510): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4510): Local Branch: 
I/Adreno-EGL( 4510): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4510): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4510):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4510): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4510): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4510): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4510): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4510): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4510): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4510): CordovaWebView is running on device made by: HTC
D/WIFI_ICON( 1118): WifiActivity: 1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/AwContents( 4510): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1270
,I/InputMethodManagerService(  906): Enable input method client, pid=4510
W/ResourceType( 4510): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4510): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41abb5c8, mServedView=org.apache.cordova.engine.SystemWebView{41a81230 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1213): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1213): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4510): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +422ms
,D/PMS     (  906): releaseWL(437996d8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42de3f70 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/JsMessageQueue( 4510): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4510): JniHelper::setJavaVM(0x41547048), pthread_self() = 1662048040
,D/JX-Cordova( 4510): jxcore cordova android initializing
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.582MB for 96598-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.662MB for 144892-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.778MB for 217334-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.954MB for 325996-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 12.228MB for 488990-byte allocation
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 13.235MB for 1100216-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 14.117MB for 1650320-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 15.477MB for 2475476-byte allocation
,I/SensorManager(  906): mEventCount = 900
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(44004018): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(425a02e0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 17.458MB for 3713210-byte allocation
,W/jxcore-log( 4510): Initializing JXcore engine
,W/jxcore-log( 4510): JXcore engine is ready
,W/jxcore-log( 4510): Starting JXcore engine
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 4510): Platform android
W/jxcore-log( 4510): 
,W/jxcore-log( 4510): Process ARCH arm
W/jxcore-log( 4510): 
,I/jxcore-log( 4510): JXcore Cordova bridge is ready!
I/jxcore-log( 4510): 
,W/jxcore-log( 4510): JXcore engine is started
,I/chromium( 4510): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  906): releaseWL(43bf5288): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(437f21e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{424b7b88: PendingIntentRecord{425acb08 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452237983962, Int=563223000
,D/PMS     (  906): acquireWL(436c18d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1232 10028 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4553 uid=10077 gids={50077}
,V/AlarmManager(  906): sending alarm PendingIntent{422c9b98: PendingIntentRecord{41cb9e08 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452237997907, Int=60000
,D/PMS     (  906): releaseWL(437f21e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(435de990): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1232 10028 null
,D/PMS     (  906): releaseWL(436c18d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1232/10028)
,I/CheckinService( 1232): Preparing to send checkin request
,I/EventLogService( 1232): Accumulating logs since 1452237948988
,W/EventLogAggregator( 1232): Unknown tag: install_package_attempt
,W/EventLogAggregator( 1232): Unknown tag: snet
,W/EventLogAggregator( 1232): Unknown tag: snet_gcore
,D/SMSBackup( 4553): SMSBackupAgentService started
,D/SMSBackup( 4553): Checking restore status
D/SMSBackup( 4553): Restore complete
,D/SMSBackup( 4553): cancelCheckAlarm
,D/SMSBackup( 4553): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3620
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3620:com.htc.task/u0a70 (adj 15): empty #17
,D/PMS     (  906): acquireWL(435cbb30): PARTIAL_WAKE_LOCK  Icing 0x1 1232 10028 null
,D/PMS     (  906): releaseWL(435cbb30): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/GoogleHttpClient( 1232): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1232): Using GMS GoogleHttpClient
D/PMS     (  906): acquireWL(435c89b8): PARTIAL_WAKE_LOCK  Icing 0x1 1232 10028 null
,D/PMS     (  906): releaseWL(435c89b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3620
,D/PMS     (  906): acquireWL(435c1578): PARTIAL_WAKE_LOCK  Icing 0x1 1232 10028 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1232/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1232/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/jxcore-log( 4510): Toggling radios to true
I/jxcore-log( 4510): 
,D/BluetoothAdapter( 4510): enable(): BT is already enabled..!
D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/WifiManager( 4510): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/CheckinRequestBuilder( 1232): awaiting user notification for token
,I/RemoteViews( 1118): com.google.android.gms (false,0)
D/PMS     (  906): releaseWL(435c1578): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/WifiService(  906): setWifiEnabled: true pid=4510, uid=10348
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1273
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
,D/WifiManager( 4510): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): TDLS: Tear down peers
I/wpa_supplicant( 1163): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiManager( 4510): reconnect: Base Package Name=com.test.thalitest, uid=10348
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41bb53c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/jxcore-log( 4510): Radios toggled
I/jxcore-log( 4510): 
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/RemoteViews.Performance( 1118): com.google.android.gms 2 7 2 12
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  906): New client listening to asynchronous messages
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4510): Received device characteristics:
I/jxcore-log( 4510): Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4510): Bluetooth name: HTC Desire 820
I/jxcore-log( 4510): Device name: HTC-HTC Desire 820
I/jxcore-log( 4510): 
I/jxcore-log( 4510): Perf Test app loaded loaded
I/jxcore-log( 4510): 
I/Choreographer( 4510): Skipped 92 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4510): check test folder
I/jxcore-log( 4510): 
,I/jxcore-log( 4510): found test : ./testFindPeers.js
I/jxcore-log( 4510): 
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1163): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1163): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1163): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb89d5bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1163):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1163): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port ,unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1163): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1163): nl80211: Ignore disconnect event triggered during reassociation
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiNative-wlan0(  906):    returned true
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): Wireless event: cmd=0x8b15 len=20
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
I/jxcore-log( 4510): found test : ./testSendData.js
I/jxcore-log( 4510): 
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/PMS     (  906): acquireWL(41e544e8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): Fast associate: Old scan results
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19739 mDataStallAlarmIntent=PendingIntent{43fdf6c8: PendingIntentRecord{42538a68 android broadcastIntent}}
I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4572 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
,D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/UsbnetStateTracker(  906): isAvailable+-
D/WifiNative-wlan0(  906):    returned true
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WISPrService( 4176): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4176): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiService(  906): New client listening to asynchronous messages
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/PMS     (  906): acquireWL(425a3988): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
,D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/libc    (  364): [NET] entry_id:5   entry:0xb8d79768  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb8d78d90  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb8d79310  removed 
D/libc    (  364): [NET] entry_id:10   entry:0xb8d796d0  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb8d79088  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb8d78fd8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb8d79248  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb8d79150  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb8d79818  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb8d79410  removed 
D/libc    (  364): [NET] entry_id:11   entry:0xb8d78e70  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 4176): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4176): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(42467dd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d6d548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1369/10028)
D/PMS     (  906): releaseWL(42d6d548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  906): releaseWL(425a3988): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
,D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  906):    returned false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
,I/MultiDex( 4572): install
,I/MultiDex( 4572): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/PMS     (  906): releaseWL(42467dd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
I/MultiDex( 4572): loading existing secondary dex files
I/MultiDex( 4572): load found 1 secondary dex files
I/MultiDex( 4572): install done
,I/ProviderInstaller( 4572): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/chromium( 4510): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4572/10028)
,I/Adreno-EGL( 4572): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4572): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4572): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4572): Local Branch: 
I/Adreno-EGL( 4572): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4572): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4572):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4572): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4572): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4572): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4572): Local Branch: 
I/Adreno-EGL( 4572): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4572): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4572):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4572): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4572): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4572): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4572): Local Branch: 
I/Adreno-EGL( 4572): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4572): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4572):                  aa63bbd948f41d15fc72f585e
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
,I/Tethering(  906): No IPv4 upstream interface, giving up.
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,I/NetworkMonitor( 3887): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(425800a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1421/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1902/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4395/10100)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3887/10154)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4395/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2433/10021)
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4598 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
D/PMS     (  906): releaseWL(425800a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4598): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4598): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4598): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4598): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4598): Preparing secondary program dexes.
,V/DexLibLoader( 4598): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4598): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4598): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4598): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4598): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4598): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4598): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4598): Dex already copied
D/OdexVerifier( 4598): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4598): Creating class loader
,V/DexLibLoader( 4598): Finished creating class loader
V/DexLibLoader( 4598): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4598): Dex already copied
D/OdexVerifier( 4598): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4598): Creating class loader
,V/DexLibLoader( 4598): Finished creating class loader
V/DexLibLoader( 4598): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4598): Dex already copied
D/OdexVerifier( 4598): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4598): Creating class loader
,V/DexLibLoader( 4598): Finished creating class loader
V/DexLibLoader( 4598): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4598): Dex already copied
D/OdexVerifier( 4598): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4598): Creating class loader
,V/DexLibLoader( 4598): Finished creating class loader
,V/DexLibLoader( 4598): Verifying classes from secondary dexes.
,D/DexLibLoader( 4598): DexLibLoader.ensureDexLoaded took 18 ms
,W/Settings( 4572): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinTask( 1232): Sending checkin request (9009 bytes)
D/libc    ( 1232): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1232): [NET] getaddrinfo-,err=8
D/libc    ( 1232): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1232): [NET] getaddrinfo-, 1
,D/libc    ( 1232): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =22e9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET]Querying server xid =22e9 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=22e9, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 1232): [NET] getaddrinfo_proxy-
E/CheckinTask( 1232): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/GoogleHttpClient( 1232): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1232/10028)
,D/PMS     (  906): releaseWL(435de990): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1232): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41df4230 that was originally bound here
E/ActivityThread( 1232): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41df4230 that was originally bound here
E/ActivityThread( 1232): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1232): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1232): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1232): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1232): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1232): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1232): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1232): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1232): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1232): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1232): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1232): 	at bks.a(SourceFile:298)
E/ActivityThread( 1232): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1232): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1232): 	at java.lang.Thread.run(Thread.java:864)
,W/dalvikvm( 4598): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1163): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1163): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1163): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1163): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 3
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 1
I/wpa_supplicant( 1163): wpa_s->is_screen_on 1
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): selected network = 2
D/wpa_supplicant( 1163): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb89d74e8  current_ssid=0x0
D/wpa_supplicant( 1163): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1163): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1163): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1163): check if in concurrent case
,I/wpa_supplicant( 1163): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1163): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1163): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1163): wpa_supplicant_associate, 1795
,D/wpa_supplicant( 1163): RSN: PMKSA cache search - network_ctx=0xb89d74e8 try_opportunistic=0
D/wpa_supplicant( 1163): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1163): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1163): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1163): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1163): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 6,
D/wpa_supplicant( 1163): nl80211: Unsubscribe mgmt frames handle 0xb89d6718 (mode change)
D/wpa_supplicant( 1163): nl80211: Subscribe to mgmt frames with non-AP handle 0xb89d6718
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb89d6718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb89d6718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb89d6718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb89d6718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb89d6718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb89d6718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb89d6718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb89d6718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb89d6718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb89d6718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1163):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1163):   * freq=2412
,D/wpa_supplicant( 1163):   * Auth Type 0
D/wpa_supplicant( 1163):   * WPA Versions 0x2
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1163): nl80211: Connect request send successfully
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1163): reply (489) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000021641255
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=1
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000107141124
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000107141128
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-78
I/wpa_supplicant( 1163): tsf=0000000107141133
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 21641255, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 107141124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 107141128, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 107141133, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4598): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1163): nl80211: Connect event
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1163): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1163): Add randomness: count=11 entropy=4
I/wpa_supplicant( 1163): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1163): TDLS: Remove peers on association
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  906): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1163): EAPOL: enable timer tick
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1163): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1163): Get randomness: len=32 entropy=5
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false,
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
I/wpa_supplicant( 1163): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb89d69f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1163):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1163): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fc2b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1163):    broadcast key
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1163): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1163): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1163): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1163): set send_ind_to_ndc = 0
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1163): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1163): EAPOL authentication completed successfully
I/wpa_supplicant( 1163): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..,
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WISPrService( 4176): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4176): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [2][0][0]
W/fb4a(:<default>):StaticBindingVerifier( 4598): Verify
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 1
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(43fe00b8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4235b618 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4235b618 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4598): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4598): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4322
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4322:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  906): acquireWL(431f1910): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1232 10028 null
,D/PMS     (  906): acquireWL(435c3090): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1232 10028 null
,D/PMS     (  906): releaseWL(431f1910): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1369): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1232/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1232/10028)
,D/PMS     (  906): releaseWL(435c3090): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1400): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  906): Recipient 4322
D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4628 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1400/10053)
,D/AutoSetting( 1400): Util - no network available!
,D/AutoSetting( 1400): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1400): service - mHandler: cancel location update
,D/AutoSetting( 1400): service -           changes count: 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1400/10053)
,W/fb4a(:<default>):UserScope( 4598): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4598): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4598): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4628): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4628): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4628): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4628): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4642 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4343
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4343:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4628/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4628/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4628/10078)
,I/ActivityManager(  906): Recipient 4343
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4598): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4659 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4251
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  906): Killing 4251:com.google.android.partnersetup/u0a31 (adj 15): empty #17
E/dalvikvm( 4598): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4598): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4598): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4598): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4598): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4598): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4598): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4598): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4598): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4598): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4598): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4598): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4598): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
I/ActivityManager(  906): Recipient 4251
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 4598): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4598): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4598): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4598): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4598): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 9.997MB for 79892-byte allocation
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4659): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4659): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4659): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4659): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4659): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 10.067MB for 84664-byte allocation
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 10.093MB for 28144-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4659/10151)
,V/WebViewChromiumFactoryProvider( 4659): Binding Chromium to main looper Looper (main, tid 1) {41a6df88}
,I/LibraryLoader( 4659): Expected native library version number "",actual native library version number ""
,I/chromium( 4659): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4659): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(43f55378): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  906): acquireWL(422fbb40): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  906): releaseWL(43f55378): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/AudioManagerAndroid( 4659): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4659): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4659): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4659): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4659): Local Branch: 
I/Adreno-EGL( 4659): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4659): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4659):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,I/NSApplication( 4659): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43557160 u0 ReceiverList{43557040 4598 com.facebook.katana/10026/u0 remote:43fdfc90}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43557160 u0 ReceiverList{43557040 4598 com.facebook.katana/10026/u0 remote:43fdfc90}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42c0ee10 u0 ReceiverList{424a3300 4598 com.facebook.katana/10026/u0 remote:435c7a60}}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4659/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4659/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4155/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4155/10160)
,D/Process (  906): killProcessQuiet, pid=4395
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4395:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4395
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  906): acquireWL(4404c860): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1421 10028 null
,D/PMS     (  906): releaseWL(4404c860): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1163): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1163): EAPOL: disable timer tick
,D/GCoreFlp( 1421): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(43fe0920): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1421 10028 null
D/PMS     (  906): releaseWL(43fe0920): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4598): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4598): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP,
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1163): Change stage from stage0 to stage3
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  906): releaseWL(43fe00b8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  906): gateway: /192.168.1.1
D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): WiFi gateway: 0x101a8c0
,I/wpa_supplicant( 1163): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19741 delay=15s
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 4176): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@4239dc40
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(43232cf8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4628/10078)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(41dc3000): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1232 10028 null
D/PMS     (  906): releaseWL(43232cf8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(425367f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1232 10028 null
D/PMS     (  906): releaseWL(41dc3000): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
I/CheckinService( 1232): Preparing to send checkin request
,I/EventLogService( 1232): Accumulating logs since 1452237997950,
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1232/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1232): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1232): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1232/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1232/10028)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1232): awaiting user notification for token
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41bb5e40 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 1 7 2 12
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4572/10028)
,I/Adreno-EGL( 4572): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4572): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4572): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4572): Local Branch: 
I/Adreno-EGL( 4572): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4572): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4572):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4572): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4572): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4572): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4572): Local Branch: 
I/Adreno-EGL( 4572): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4572): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4572):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4572): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4572): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4572): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4572): Local Branch: 
I/Adreno-EGL( 4572): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4572): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4572):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1118): WifiActivity: 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/dalvikvm( 4510): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4510): threadid=1: thread exiting with uncaught exception (group=0x4163fe30)
,E/ActivityManager(  906): App crashed! Process: com.test.thalitest
D/PMS     (  906): releaseWL(41e544e8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
E/AndroidRuntime( 4510): FATAL EXCEPTION: main
E/AndroidRuntime( 4510): Process: com.test.thalitest, PID: 4510
E/AndroidRuntime( 4510): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4510): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4510): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4510): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4510): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4510): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4510): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4510): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4510): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4510): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4510): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4510): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4510): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4510): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4510): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4510): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4510): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4510): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4510): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  906):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
,W/Settings( 4572): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PMS     (  906): acquireWL(425d13b8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/asset   (  906): Copying FileAsset 0x62c47aa0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/CheckinTask( 1232): Sending checkin request (9006 bytes)
D/libc    ( 1232): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1232): [NET] getaddrinfo-,err=8
D/libc    ( 1232): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1232): [NET] getaddrinfo-, 1
,D/libc    ( 1232): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =58d9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/CaptivePortalTracker(  906): NoActiveNetworkState
I/acms    ( 1902): Checking Certificates
I/acms    ( 1902): Checking Developer Certificates
I/acms    ( 1902): Checking Application Certificates
I/acms    ( 1902): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1902): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1902): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1902): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1902): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1902): Updating next query delay: 75600000
I/mlserverapp( 1902): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1902): cancelACMSProgrammedChecks
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000),
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1421/10028)
D/PMS     (  906): acquireWL(42356820): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1902/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3924/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4628/10078)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/NetworkMonitor( 3887): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3887/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(435bce60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
D/PMS     (  906): releaseWL(435bce60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(42356820): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 236
D/libc    (  364): [NET]res_nsend:resplen=84
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1232): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2433/10021)
,D/PMS     (  906): acquireWL(43ad1850): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1232 10028 null
,D/PMS     (  906): releaseWL(43ad1850): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1369): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1369): [NET] getaddrinfo-, 1
,D/libc    ( 1369): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d716 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  906): acquireWL(42532e68): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1369 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1232/10028)
,D/AutoSetting( 1400): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4628): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4628): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1400/10053)
,D/AutoSetting( 1400): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1400): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1400): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1400): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1400): service - handleMessage() setting current location null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4659/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1400/10053)
D/AutoSetting( 1400): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1400): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1232): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1232): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 226
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1369): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4155/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4155/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 13.634MB for 1821008-byte allocation
,D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
,D/PMS     (  906): acquireWL(43840250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/PMS     (  906): releaseWL(43840250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=7 [13][1][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-55 , oldRssi= -200
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,W/ActivityManager(  906): Activity pause timeout for ActivityRecord{43fe5d38 u0 com.test.thalitest/.MainActivity t2 f}
,W/fb4a(:<default>):UserScope( 4598): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4598): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/FeedHostManager( 1270): [onResume]
,I/FeedProviderManager( 1270): onResume
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/SocialFeedProvider( 1270): +onResume
I/SocialFeedProvider( 1270): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1270): -onResume
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1270/10075)
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/PMS     (  906): acquireWL(425aa690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/PMS     (  906): releaseWL(425aa690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): releaseWL(425d13b8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1232/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1232/10028)
,D/Process (  906): killProcessQuiet, pid=4411
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  906): Killing 4411:com.htc.backup/1000 (adj 15): empty #17
D/PMS     (  906): acquireWL(43f67ff8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
,D/GCM     ( 1369): Connected
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  906): releaseWL(42532e68): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  906): releaseWL(43f67ff8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(4288dea0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,D/GCM     ( 1369): Message class mpf
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
D/PMS     (  906): releaseWL(4288dea0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(430cfc90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/PMS     (  906): releaseWL(430cfc90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1232): awaiting user notification for token
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41e2a800 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 1 10 2 12
I/ActivityManager(  906): Recipient 4411
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CheckinTask( 1232): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1232): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1232/10028)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4598): Called registerBroadcastReceiver twice.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1232/10028)
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(425367f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1232): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b11578 that was originally bound here
E/ActivityThread( 1232): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b11578 that was originally bound here
E/ActivityThread( 1232): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1232): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1232): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1232): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1232): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1232): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1232): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1232): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1232): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1232): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1232): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1232): 	at bks.a(SourceFile:298)
E/ActivityThread( 1232): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1232): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1232): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1369): GCM config loaded
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026),
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/PMS     (  906): releaseWL(422fbb40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [3][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-,err=8
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/WIFI_ICON( 1118): WifiActivity: 1
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a2c5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 14
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42017e20
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/PMS     (  906): mWirelessDisplayManager is null
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42017e20, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422c1570
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@41e73de8
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 374ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,D/PMS     (  906): OOBE c monitor 11
I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1258): ScreenObserver: OFF
,D/NfcService( 1258): applyRouting - 0
I/InputMethodManagerService(  906): Disable input method client, pid=4510
D/PMS     (  906): acquireWL(43fe5910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43b51ed0)
,D/NfcService( 1258): applyRouting -2
I/BatteryService(  906): n_update end
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(425192b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMS     (  906): releaseWL(425192b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(43fe5910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  906): onScreenOn
,D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/MtpService( 2433): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2433): [MTP][onReceive]-
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,D/NfcService( 1258): applyRouting - 0
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1258): applyRouting -2
,I/ClockThread( 1118): stop update clock
D/PMS     (  906): acquireWL(4383e908): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  906): releaseWL(4383e908): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19742 delay=15s
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4758 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): SET_SCREEN_ON:On
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1163): BG scan when screen On
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): Match BG scan, scan!
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =2
,I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/WifiNative-wlan0(  906):    returned true
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1118): WifiActivity: 3
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/NetworkPolicy(  906): updateScreenOn: false
,I/GAV2    ( 4659): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 4758): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4758): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(44009130): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4758 1000 null
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1805): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1805): onScreenOn: 1452238006184
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1805): onScreenOn: 1452238006184
D/PMS     (  906): releaseWL(44009130): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  906): acquireWL(43fe3408): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1421 10028 null
D/PMS     (  906): releaseWL(43fe3408): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4758): getMobilePolicyEnabled, result = true
,D/Process (  906): killProcessQuiet, pid=4382
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1400): receiver - intent: android.intent.action.USER_PRESENT
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422c1570
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422c1570, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@41e73de8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): Killing 4382:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(439c2d90): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,I/ActivityManager(  906): Recipient 4382
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1400): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c2c350
I/SocialFeedProvider( 1270): +onPause
,I/SocialFeedProvider( 1270): -onPause
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19742 mDataStallAlarmIntent=PendingIntent{42535788: PendingIntentRecord{4244e200 android broadcastIntent}}
D/TetherSettings( 4176): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4176): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4176): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4176): Cust_ConnectToPC   : spcsc>false
D/        ( 4176): Cust_ConnectToPC   : IPT>true
,D/        ( 4176): Cust_ConnectToPC   : Singel_USB>false
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): releaseWL(439c2d90): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  906): acquireWL(43759de8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
W/Settings( 4176): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4176): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4176): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4176): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4176): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4176): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4176): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4176): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4176):  defaultType:0
,W/ContextImpl( 4758): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4758): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4758): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4758): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,D/PMS     (  906): acquireWL(43759cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1421 10028 null
,D/PMS     (  906): acquireWL(436bed38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1421 10028 null
,D/PMS     (  906): releaseWL(43759cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(436bed38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): SET_SCREEN_ON:Off
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1163): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41e73de8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41e73de8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41e73de8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41e73de8
,E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42035b78 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42035b78 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1247): start background delete task...
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
,D/AutoSetting( 1400): service - mHandler: cancel location update
,D/AutoSetting( 1400): service -           changes count: 0
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/DotMatrix( 1584): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(42dd6c60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1421 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1805): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1805): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1805): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1805): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1805): onScreenOff
D/PMS     (  906): releaseWL(42dd6c60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(43759de8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1163): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=12 entropy=0
D/wpa_supplicant( 1163): Add randomness: count=13 entropy=1
D/wpa_supplicant( 1163): Add randomness: count=14 entropy=2
D/wpa_supplicant( 1163): Add randomness: count=15 entropy=3
D/wpa_supplicant( 1163): Add randomness: count=16 entropy=4
D/wpa_supplicant( 1163): Add randomness: count=17 entropy=5
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplica,nt( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1163): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=18 entropy=6
D/wpa_supplicant( 1163): Add randomness: count=19 entropy=7
D/wpa_supplicant( 1163): Add randomness: count=20 entropy=8
D/wpa_supplicant( 1163): Add randomness: count=21 entropy=9
D/wpa_supplicant( 1163): Add randomness: count=22 entropy=10
D/wpa_supplicant( 1163): Add randomness: count=23 entropy=11
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: DISCONNECTED -> INACTIVE
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@423296d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@423296d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@423296d8 target=com.android.internal.util.StateMachine$SmHandler }
D/Process (  906): killProcessQuiet, pid=4435
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/ActivityManager(  906): Killing 4435:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1163): reply (779) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000114999051
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=1
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000114999076
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000114999086
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-78
I/wpa_supplicant( 1163): tsf=0000000114999099
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000114999109
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000114999122
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ####
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 114999051, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 114999076, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 114999086, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 114999099, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 114999109, distance: ?(cm), distanceSd: ?(cm)
I/ActivityManager(  906): Recipient 4435
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 114999122, distance: ?(cm), distanceSd: ?(cm)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/AutoSetting( 1501): service - handleMessage() stop self
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4032
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4032:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4032
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 10.958MB for 27710-byte allocation
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 10.980MB for 41560-byte allocation
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 11.013MB for 62336-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 11.051MB for 65480-byte allocation
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 11.058MB for 44212-byte allocation
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 11.071MB for 56766-byte allocation
,D/libc    ( 4598): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4598): [NET] getaddrinfo-,err=8
D/libc    ( 4598): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4598): [NET] getaddrinfo-, 1
,D/libc    ( 4598): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6444 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 26
D/libc    (  364): [NET]res_nsend:resplen=93
D/libc    (  364): [NET]res_queryN: exit 3, ancount=3
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4598): [NET] getaddrinfo_proxy-, success
I/global  ( 4598): call createSocket() return a new socket.
D/libc    ( 4598): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4598): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4598): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4598): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(423cce58): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4598 10026 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 11.229MB for 55842-byte allocation
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 11.269MB for 108446-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4598/10026)
,W/ActivityManager(  906): Activity destroy timeout for ActivityRecord{43fe5d38 u0 com.test.thalitest/.MainActivity t2 f}
,I/global  ( 4598): I/O error closing connection
I/global  ( 4598): java.net.SocketException: Socket is closed
I/global  ( 4598): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4598): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4598): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4598): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4598): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4598): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4598): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4598): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4598): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4598): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4598): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4598): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4598): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4598): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4598): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4598): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4598): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4598): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4598): Removing a connection that never existed!
D/PMS     (  906): releaseWL(423cce58): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4252a0e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dc4d8: PendingIntentRecord{420e1940 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=126843, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4252a0e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  906): acquireWL(42560d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42560d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
D/wpa_supplicant( 1163): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=24 entropy=12
D/wpa_supplicant( 1163): Add randomness: count=25 entropy=13
D/wpa_supplicant( 1163): Add randomness: count=26 entropy=14
D/wpa_supplicant( 1163): Add randomness: count=27 entropy=15
D/wpa_supplicant( 1163): Add randomness: count=28 entropy=16
D/wpa_supplicant( 1163): Add randomness: count=29 entropy=17
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1,163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
D/wpa_supplicant( 1163): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=30 entropy=18
D/wpa_supplicant( 1163): Add randomness: count=31 entropy=19
D/wpa_supplicant( 1163): Add randomness: count=32 entropy=20
D/wpa_supplicant( 1163): Add randomness: count=33 entropy=21
D/wpa_supplicant( 1163): Add randomness: count=34 entropy=22
D/wpa_supplicant( 1163): Add randomness: count=35 entropy=23
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (779) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000132444768
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=1
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48,
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000132444797
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000132444807
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
,I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-78
I/wpa_supplicant( 1163): tsf=0000000132444818
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000132444837
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000132444827
,I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 132444768, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 132444797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 132444807, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 132444818, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 132444837, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 132444827, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1400): service - mHandler: update timezone
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1501): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1584): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1501): service - mHandler: update timezone
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1501): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1501): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1118): removeNotification.gc:54
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41e58840 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 8 3 11
,D/PMS     (  906): acquireWL(43a7cc60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42473ab8: PendingIntentRecord{420b46a0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141313, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  906): sending alarm PendingIntent{42caa328: PendingIntentRecord{4245a948 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143786, Int=0
D/PMS     (  906): acquireWL(4360f1c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(43a7cc60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  906): acquireWL(42b055f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =51f3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  906): releaseWL(42b055f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1400): service - handleMessage() stop self
,D/AutoSetting( 1400): service - onDestroy() END
,D/AutoSetting( 1400): service - handleMessage() quit looper
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/Process (  906): killProcessQuiet, pid=3924
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3924:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3924
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(4360f1c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1163): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=36 entropy=24
D/wpa_supplicant( 1163): Add randomness: count=37 entropy=25
D/wpa_supplicant( 1163): Add randomness: count=38 entropy=26
D/wpa_supplicant( 1163): Add randomness: count=39 entropy=27
D/wpa_supplicant( 1163): Add randomness: count=40 entropy=28
D/wpa_supplicant( 1163): Add randomness: count=41 entropy=29
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1163): BSS: last_scan_res_used=6/32 last_scan_full=0
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,D/wpa_supplicant( 1163): Add randomness: count=42 entropy=30
D/wpa_supplicant( 1163): Add randomness: count=43 entropy=31
D/wpa_supplicant( 1163): Add randomness: count=44 entropy=32
D/wpa_supplicant( 1163): Add randomness: count=45 entropy=33
D/wpa_supplicant( 1163): Add randomness: count=46 entropy=34
D/wpa_supplicant( 1163): Add randomness: count=47 entropy=35
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (926) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000149865444
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=1
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000132444797
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000149865472
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-81
I/wpa_supplicant( 1163): tsf=0000000149865494
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000149865483
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000149865503
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000149865513
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 149865444, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 132444797, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 149865472, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 149865494, distance: ?(cm),, distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 149865483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 149865503, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 149865513, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 7 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43fe3b20 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=48 entropy=36
D/wpa_supplicant( 1163): Add randomness: count=49 entropy=37
D/wpa_supplicant( 1163): Add randomness: count=50 entropy=38
D/wpa_supplicant( 1163): Add randomness: count=51 entropy=39
D/wpa_supplicant( 1163): Add randomness: count=52 entropy=40
D/wpa_supplicant( 1163): Add randomness: count=53 entropy=41
D/wpa_supplicant( 1163): Add randomness: count=54 entropy=42
D/wpa_supplicant( 1163): Add randomness: count=55 entropy=43
D/wpa_supplicant( 1163): Add randomness: count=56 entropy=44
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( ,1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 8: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=57 entropy=45
D/wpa_supplicant( 1163): Add randomness: count=58 entropy=46
D/wpa_supplicant( 1163): Add randomness: count=59 entropy=47
D/wpa_supplicant( 1163): Add randomness: count=60 entropy=48
D/wpa_supplicant( 1163): Add randomness: count=61 entropy=49
D/wpa_supplicant( 1163): Add randomness: count=62 entropy=50
D/wpa_supplicant( 1163): Add randomness: count=63 entropy=51
D/wpa_supplicant( 1163): Add randomness: count=64 entropy=52
D/wpa_supplicant( 1163): Add randomness: count=65 entropy=53,
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000167315887
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=1
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000167315913
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
,I/wpa_supplicant( 1163): tsf=0000000167315925
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000167315936
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000149865483
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000167315966
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000167315945
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000167315976
I/wpa_supplicant( 1163): f
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 167315887, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 167315913, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 167315925, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 167315936, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 149865483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 167315966, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
D/WifiStateMachine(  906): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 167315945, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 167315976, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 167315956, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/AutoSetting( 1501): service - handleMessage() stop self
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4453
,I/ActivityManager(  906): Killing 4453:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4453
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43606f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,D/PMS     (  906): releaseWL(43606f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=66 entropy=54
D/wpa_supplicant( 1163): Add randomness: count=67 entropy=55
D/wpa_supplicant( 1163): Add randomness: count=68 entropy=56
D/wpa_supplicant( 1163): Add randomness: count=69 entropy=57
D/wpa_supplicant( 1163): Add randomness: count=70 entropy=58
D/wpa_supplicant( 1163): Add randomness: count=71 entropy=59
D/wpa_supplicant( 1163): Add randomness: count=72 entropy=60
D/wpa_supplicant( 1163): Add randomness: count=73 entropy=61
D/wpa_supplicant( 1163): Add randomness: count=74 entropy=62
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wp,a_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=75 entropy=63
D/wpa_supplicant( 1163): Add randomness: count=76 entropy=64
D/wpa_supplicant( 1163): Add randomness: count=77 entropy=65
D/wpa_supplicant( 1163): Add randomness: count=78 entropy=66
D/wpa_supplicant( 1163): Add randomness: count=79 entropy=67
D/wpa_supplicant( 1163): Add randomness: count=80 entropy=68
D/wpa_supplicant( 1163): Add randomness: count=81 entropy=69
D/wpa_supplicant( 1163): Add randomness: count=82 entropy=70
D/wpa_supplicant( 1163): Add randomness: count=83 entropy=71
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 trie,s=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1163): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000184775721
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=1
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000184775748
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000184775758
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000184775769
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000184775822
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000167315966
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000184775788
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000167315976
I/wpa_supplicant( 1163): f
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 184775721, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 184775748, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 184775758, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 184775769, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 184775822, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 167315966, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 184775788, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 167315976, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList,
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): 8: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 184775798, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43bf42d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dc4d8: PendingIntentRecord{420e1940 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=186842, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bf42d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42fb3498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42fb3498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=84 entropy=72
D/wpa_supplicant( 1163): Add randomness: count=85 entropy=73
D/wpa_supplicant( 1163): Add randomness: count=86 entropy=74
D/wpa_supplicant( 1163): Add randomness: count=87 entropy=75
D/wpa_supplicant( 1163): Add randomness: count=88 entropy=76
D/wpa_supplicant( 1163): Add randomness: count=89 entropy=77
D/wpa_supplicant( 1163): Add randomness: count=90 entropy=78
D/wpa_supplicant( 1163): Add randomness: count=91 entropy=79
D/wpa_supplicant( 1163): Add randomness: count=92 entropy=80
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->i,s_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=93 entropy=81
D/wpa_supplicant( 1163): Add randomness: count=94 entropy=82
D/wpa_supplicant( 1163): Add randomness: count=95 entropy=83
D/wpa_supplicant( 1163): Add randomness: count=96 entropy=84
D/wpa_supplicant( 1163): Add randomness: count=97 entropy=85
D/wpa_supplicant( 1163): Add randomness: count=98 entropy=86
D/wpa_supplicant( 1163): Add randomness: count=99 entropy=87
D/wpa_supplicant( 1163): Add randomness: count=100 entropy=88
D/wpa_supplicant( 1163): Add randomness: count=101 entropy=89
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tr,ies=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000202205442
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=1
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000202205472
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC,
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000202205486
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000202205499
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
,I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000184775822
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000202205538
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000202205552
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
,I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000167315976
I/wpa_supplicant( 1163): f
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 202205442, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 202205472, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 202205486, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 202205499, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 184775822, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -86, frequency: 2437, timestamp: 202205538, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 202205552, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 167315976, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 202205510, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=102 entropy=90
D/wpa_supplicant( 1163): Add randomness: count=103 entropy=91
D/wpa_supplicant( 1163): Add randomness: count=104 entropy=92
D/wpa_supplicant( 1163): Add randomness: count=105 entropy=93
D/wpa_supplicant( 1163): Add randomness: count=106 entropy=94
D/wpa_supplicant( 1163): Add randomness: count=107 entropy=95
D/wpa_supplicant( 1163): Add randomness: count=108 entropy=96
D/wpa_supplicant( 1163): Add randomness: count=109 entropy=97
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie,_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=110 entropy=98
D/wpa_supplicant( 1163): Add randomness: count=111 entropy=99
D/wpa_supplicant( 1163): Add randomness: count=112 entropy=100
D/wpa_supplicant( 1163): Add randomness: count=113 entropy=101
D/wpa_supplicant( 1163): Add randomness: count=114 entropy=102
D/wpa_supplicant( 1163): Add randomness: count=115 entropy=103
D/wpa_supplicant( 1163): Add randomness: count=116 entropy=104
D/wpa_supplicant( 1163): Add randomness: count=117 entropy=105
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - t,ype=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000219691888
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=1
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000202205472
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000219691916
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000219691929
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000219691939
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000219691963
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1,163): tsf=0000000219691984
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000219691973
I/wpa_supplicant( 1163): f
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 219691888, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 202205472, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 219691916, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 219691929, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 219691939, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -86, frequency: 2437, timestamp: 219691963, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 219691984, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 219691973, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 219691951, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42569180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{424eb508: PendingIntentRecord{4333df50 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228069, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4805 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{4253dec0: PendingIntentRecord{422b7010 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452238113550, Int=10800000
,D/PMS     (  906): releaseWL(42569180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4805/10047)
,D/Process (  906): killProcessQuiet, pid=4468
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4468:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4468
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1232/10028)
,D/PMS     (  906): acquireWL(4383fb40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4243d5e8: PendingIntentRecord{4333df50 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=233069, Int=0
,D/PMS     (  906): releaseWL(4383fb40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  906): acquireWL(43612bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  906): n_update end
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(43612bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=118 entropy=106
D/wpa_supplicant( 1163): Add randomness: count=119 entropy=107
D/wpa_supplicant( 1163): Add randomness: count=120 entropy=108
D/wpa_supplicant( 1163): Add randomness: count=121 entropy=109
D/wpa_supplicant( 1163): Add randomness: count=122 entropy=110
D/wpa_supplicant( 1163): Add randomness: count=123 entropy=111
D/wpa_supplicant( 1163): Add randomness: count=124 entropy=112
D/wpa_supplicant( 1163): Add randomness: count=125 entropy=113
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
,I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=126 entropy=114
D/wpa_supplicant( 1163): Add randomness: count=127 entropy=115
D/wpa_supplicant( 1163): Add randomness: count=128 entropy=116
D/wpa_supplicant( 1163): Add randomness: count=129 entropy=117
D/wpa_supplicant( 1163): Add randomness: count=130 entropy=118
D/wpa_supplicant( 1163): Add randomness: count=131 entropy=119
D/wpa_supplicant( 1163): Add randomness: count=132 entropy=120
D/wpa_supplicant( 1163): Add randomness: count=133 entropy=121
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA s,ubelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1103) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000237106845
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000237106886
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000237106906
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000237106923
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000237106983
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000237106963
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000219691973
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=8
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=246
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMa,chine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 237106845, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 237106886, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 237106906, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 237106923, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -86, frequency: 2437, timestamp: 237106983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 237106963, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 219691973, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 237106945, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43796718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dc4d8: PendingIntentRecord{420e1940 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=246842, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43796718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(434a4640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(434a4640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=134 entropy=122
D/wpa_supplicant( 1163): Add randomness: count=135 entropy=123
D/wpa_supplicant( 1163): Add randomness: count=136 entropy=124
D/wpa_supplicant( 1163): Add randomness: count=137 entropy=125
D/wpa_supplicant( 1163): Add randomness: count=138 entropy=126
D/wpa_supplicant( 1163): Add randomness: count=139 entropy=127
D/wpa_supplicant( 1163): Add randomness: count=140 entropy=128
D/wpa_supplicant( 1163): Add randomness: count=141 entropy=129
D/wpa_supplicant( 1163): Add randomness: count=142 entropy=130
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2,p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 8: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=143 entropy=131
D/wpa_supplicant( 1163): Add randomness: count=144 entropy=132
D/wpa_supplicant( 1163): Add randomness: count=145 entropy=133
D/wpa_supplicant( 1163): Add randomness: count=146 entropy=134
D/wpa_supplicant( 1163): Add randomness: count=147 entropy=135
D/wpa_supplicant( 1163): Add randomness: count=148 entropy=136
D/wpa_supplicant( 1163): Add randomness: count=149 entropy=137
D/wpa_supplicant( 1163): Add randomness: count=150 entropy=138
D/wpa_supplicant( 1163): Add randomness: count=151 entropy=139
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
,D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1163): reply (1248) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000254535770
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000254535800
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700,
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000254535813
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000237106923
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000254535853
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437,
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000254535842
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000254535863
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=8
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=246
,D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 254535770, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 254535800, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 254535813, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 237106923, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 254535853, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 254535842, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 254535863, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 254535833, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 8: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -90, frequency: 2437, timestamp: 254535874, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  67, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  67, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=152 entropy=140
D/wpa_supplicant( 1163): Add randomness: count=153 entropy=141
D/wpa_supplicant( 1163): Add randomness: count=154 entropy=142
D/wpa_supplicant( 1163): Add randomness: count=155 entropy=143
D/wpa_supplicant( 1163): Add randomness: count=156 entropy=144
D/wpa_supplicant( 1163): Add randomness: count=157 entropy=145
D/wpa_supplicant( 1163): Add randomness: count=158 entropy=146
D/wpa_supplicant( 1163): Add randomness: count=159 entropy=147
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplican,t( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1163): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=160 entropy=148
D/wpa_supplicant( 1163): Add randomness: count=161 entropy=149
D/wpa_supplicant( 1163): Add randomness: count=162 entropy=150
D/wpa_supplicant( 1163): Add randomness: count=163 entropy=151
D/wpa_supplicant( 1163): Add randomness: count=164 entropy=152
D/wpa_supplicant( 1163): Add randomness: count=165 entropy=153
D/wpa_supplicant( 1163): Add randomness: count=166 entropy=154
D/wpa_supplicant( 1163): Add randomness: count=167 entropy=155
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: W,FA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  906): getDiscoveryDongleList
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1163): reply (1248) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000271953278
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000271953306
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000271953318
I/wpa_su,pplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000271953327
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000271953350
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000271953374
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000271953362
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=8
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=246
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 271953278, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 271953306, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 271953318, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 271953327, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 271953350, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 271953374, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 271953362, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 254535833, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -90, frequency: 2437, timestamp: 254535874, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  67, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  67, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=168 entropy=156
D/wpa_supplicant( 1163): Add randomness: count=169 entropy=157
D/wpa_supplicant( 1163): Add randomness: count=170 entropy=158
D/wpa_supplicant( 1163): Add randomness: count=171 entropy=159
D/wpa_supplicant( 1163): Add randomness: count=172 entropy=160
D/wpa_supplicant( 1163): Add randomness: count=173 entropy=161
D/wpa_supplicant( 1163): Add randomness: count=174 entropy=162
D/wpa_supplicant( 1163): Add randomness: count=175 entropy=163
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplican,t( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=176 entropy=164
D/wpa_supplicant( 1163): Add randomness: count=177 entropy=165
D/wpa_supplicant( 1163): Add randomness: count=178 entropy=166
D/wpa_supplicant( 1163): Add randomness: count=179 entropy=167
D/wpa_supplicant( 1163): Add randomness: count=180 entropy=168
D/wpa_supplicant( 1163): Add randomness: count=181 entropy=169
D/wpa_supplicant( 1163): Add randomness: count=182 entropy=170
D/wpa_supplicant( 1163): Add randomness: count=183 entropy=171
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1103) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000289375656
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000289375683
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000289375694
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000289375714
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
,I/wpa_supplicant( 1163): tsf=0000000289375704
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000289375724
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000289375744
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=8
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=246
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 289375656, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 289375683, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 289375694, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 289375714, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 289375704, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 289375724, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 289375744, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 289375734, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(436b3bc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436b3bc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=184 entropy=172
D/wpa_supplicant( 1163): Add randomness: count=185 entropy=173
D/wpa_supplicant( 1163): Add randomness: count=186 entropy=174
D/wpa_supplicant( 1163): Add randomness: count=187 entropy=175
D/wpa_supplicant( 1163): Add randomness: count=188 entropy=176
D/wpa_supplicant( 1163): Add randomness: count=189 entropy=177
D/wpa_supplicant( 1163): Add randomness: count=190 entropy=178
D/wpa_supplicant( 1163): Add randomness: count=191 entropy=179
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=192 entropy=180
D/wpa_supplicant( 1163): Add randomness: count=193 entropy=181
D/wpa_supplicant( 1163): Add randomness: count=194 entropy=182
D/wpa_supplicant( 1163): Add randomness: count=195 entropy=183
D/wpa_supplicant( 1163): Add randomness: count=196 entropy=184
D/wpa_supplicant( 1163): Add randomness: count=197 entropy=185
D/wpa_supplicant( 1163): Add randomness: count=198 entropy=186
D/wpa_supplicant( 1163): Add randomness: count=199 entropy=187
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blackl,ist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1103) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000306802783
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000306802810
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-83
I/wpa_supplicant( 1163): tsf=0000000306802842
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000306802832
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000306802822
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000306802851
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:,34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000306802877
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=8
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=246
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 306802783, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 306802810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 306802842, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 306802832, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 306802822, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 306802851, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 306802877, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 306802865, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(427eae28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dc4d8: PendingIntentRecord{420e1940 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=306842, Int=0,
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427eae28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43ac5390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43ac5390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=200 entropy=188
D/wpa_supplicant( 1163): Add randomness: count=201 entropy=189
D/wpa_supplicant( 1163): Add randomness: count=202 entropy=190
D/wpa_supplicant( 1163): Add randomness: count=203 entropy=191
D/wpa_supplicant( 1163): Add randomness: count=204 entropy=192
D/wpa_supplicant( 1163): Add randomness: count=205 entropy=193
D/wpa_supplicant( 1163): Add randomness: count=206 entropy=194
D/wpa_supplicant( 1163): Add randomness: count=207 entropy=195
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplican,t( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=208 entropy=196
D/wpa_supplicant( 1163): Add randomness: count=209 entropy=197
D/wpa_supplicant( 1163): Add randomness: count=210 entropy=198
D/wpa_supplicant( 1163): Add randomness: count=211 entropy=199
D/wpa_supplicant( 1163): Add randomness: count=212 entropy=200
D/wpa_supplicant( 1163): Add randomness: count=213 entropy=201
D/wpa_supplicant( 1163): Add randomness: count=214 entropy=202
D/wpa_supplicant( 1163): Add randomness: count=215 entropy=203
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1103) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000324194996
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000324195023
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
,I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000324195034
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000324195053
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000324195043
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000324195086
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS],
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000324195076
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=8
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=246
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 324194996, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 324195023, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 324195034, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 324195053, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 324195043, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 324195086, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 324195076, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 324195065, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 8 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
,D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
,D/wpa_supplicant( 1163): Add randomness: count=216 entropy=204
D/wpa_supplicant( 1163): Add randomness: count=217 entropy=205
D/wpa_supplicant( 1163): Add randomness: count=218 entropy=206
D/wpa_supplicant( 1163): Add randomness: count=219 entropy=207
D/wpa_supplicant( 1163): Add randomness: count=220 entropy=208
D/wpa_supplicant( 1163): Add randomness: count=221 entropy=209
D/wpa_supplicant( 1163): Add randomness: count=222 entropy=210
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
,I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
,I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=223 entropy=211
D/wpa_supplicant( 1163): Add randomness: count=224 entropy=212
D/wpa_supplicant( 1163): Add randomness: count=225 entropy=213
D/wpa_supplicant( 1163): Add randomness: count=226 entropy=214
D/wpa_supplicant( 1163): Add randomness: count=227 entropy=215
,D/wpa_supplicant( 1163): Add randomness: count=228 entropy=216
D/wpa_supplicant( 1163): Add randomness: count=229 entropy=217
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
,I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1103) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000341609520
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000341609548,
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-73
I/wpa_supplicant( 1163): tsf=0000000341609559
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000341609568
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000324195043
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000341609599
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000341609588
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=8
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=246
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 341609520, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 341609548, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 341609559, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 341609568, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 324195043, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 341609599, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 341609588, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 341609578, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4416b6e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(4416b6e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
,I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=230 entropy=218
D/wpa_supplicant( 1163): Add randomness: count=231 entropy=219
D/wpa_supplicant( 1163): Add randomness: count=232 entropy=220
D/wpa_supplicant( 1163): Add randomness: count=233 entropy=221
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (4 BSSes),
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=234 entropy=222
D/wpa_supplicant( 1163): Add randomness: count=235 entropy=223
D/wpa_supplicant( 1163): Add randomness: count=236 entropy=224
D/wpa_supplicant( 1163): Add randomness: count=237 entropy=225
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (960) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000341609520
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000358985317
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-76
I/wpa_supplicant( 1163): tsf=0000000358985329
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000341609568
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000358985338
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000341609588
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=8
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000341609578
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 341609520, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 358985317, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 358985329, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 341609568, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 358985338, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 341609588, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 341609578, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (7) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0,
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42da5ca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dc4d8: PendingIntentRecord{420e1940 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=366842, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42da5ca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,W/GLSActivity( 1369): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1369): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1369): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1369): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1369): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1369): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1369): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1369): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4120): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4120): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4120): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4120): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4120): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4120): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4120): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4120): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41e58be0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 1 12 3 12
,D/libc    ( 4120): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4120): [NET] getaddrinfo-,err=8
D/libc    ( 4120): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4120): [NET] getaddrinfo-, 1
,D/libc    ( 4120): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =14a8 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 207
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4120): [NET] getaddrinfo_proxy-, success
,I/global  ( 4120): call createSocket() return a new socket.
D/libc    ( 4120): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4120): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4120): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4120): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(425c75f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425c75f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1163): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=238 entropy=226
D/wpa_supplicant( 1163): Add randomness: count=239 entropy=227
D/wpa_supplicant( 1163): Add randomness: count=240 entropy=228
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0,
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1163): BSS: last_scan_res_used=3/32 last_scan_full=0
,D/wpa_supplicant( 1163): Add randomness: count=241 entropy=229
D/wpa_supplicant( 1163): Add randomness: count=242 entropy=230
,D/wpa_supplicant( 1163): Add randomness: count=243 entropy=231
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (523) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000376364810
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000376364836
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-76
I/wpa_supplicant( 1163): tsf=0000000376364847
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000358985338
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 376364810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 376364836, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 376364847, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 358985338, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1163): nl80211: Event message available,
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50,
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
,D/wpa_supplicant( 1163): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=244 entropy=232
D/wpa_supplicant( 1163): Add randomness: count=245 entropy=233
D/wpa_supplicant( 1163): Add randomness: count=246 entropy=234
D/wpa_supplicant( 1163): Add randomness: count=247 entropy=235
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1163): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=248 entropy=236
D/wpa_supplicant( 1163): Add randomness: count=249 entropy=237
D/wpa_supplicant( 1163): Add randomness: count=250 entropy=238
D/wpa_supplicant( 1163): Add randomness: count=251 entropy=239
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant,( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (520) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000393776974
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000393777000
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-78
I/wpa_supplicant( 1163): tsf=0000000376364847
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000393777020
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/Conn,ectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 393776974, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 393777000, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 376364847, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 393777020, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/Process ( 4510): killProcess, pid=4510
,D/Process ( 4510): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  906): Disable input method client, pid=4510
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  906): channel '41fcdd30 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '41fcdd30 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '41fcdd30 com.test.thalitest.MainActivity (s)'
I/ActivityManager(  906): Recipient 4510
I/WindowManager(  906): WINDOW DIED Window{41fcdd30 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  906): Process com.test.thalitest (pid 4510) has died.
D/WifiService(  906): Client connection lost with reason: 4
,W/WindowManager(  906): Failed looking up window
W/WindowManager(  906): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42d20138 does not exist
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  906): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  906): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  906): WIN DEATH: null
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-92
D/wpa_supplicant( 1163): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=252 entropy=240
D/wpa_supplicant( 1163): Add randomness: count=253 entropy=241
D/wpa_supplicant( 1163): Add randomness: count=254 entropy=242
D/wpa_supplicant( 1163): Add randomness: count=255 entropy=243
D/wpa_supplicant( 1163): Add randomness: count=256 entropy=244
D/wpa_supplicant( 1163): Add randomness: count=257 entropy=245
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 w,api_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-92
D/wpa_supplicant( 1163): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=258 entropy=246
D/wpa_supplicant( 1163): Add randomness: count=259 entropy=247
D/wpa_supplicant( 1163): Add randomness: count=260 entropy=248
D/wpa_supplicant( 1163): Add randomness: count=261 entropy=249
D/wpa_supplicant( 1163): Add randomness: count=262 entropy=250
D/wpa_supplicant( 1163): Add randomness: count=263 entropy=251
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/Wire,lessDisplayService(  906): getDiscoveryDongleList
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
,I/wpa_supplicant( 1163): reply (814) for get BSS: id=0
,I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000411215758
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000411215788
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-78
I/wpa_supplicant( 1163): tsf=0000000411215804
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-88,
I/wpa_supplicant( 1163): tsf=0000000411215829
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000411215815
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=12
I/wpa_supplicant( 1163): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-92
I/wpa_supplicant( 1163): tsf=0000000411215841
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1163): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 411215758, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 411215788, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 411215804, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 411215829, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 411215815, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -92, frequency: 2437, timestamp: 411215841, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-92], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(438856c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dc4d8: PendingIntentRecord{420e1940 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=426843, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438856c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=264 entropy=252
D/wpa_supplicant( 1163): Add randomness: count=265 entropy=253
D/wpa_supplicant( 1163): Add randomness: count=266 entropy=254
D/wpa_supplicant( 1163): Add randomness: count=267 entropy=255
D/wpa_supplicant( 1163): Add randomness: count=268 entropy=256
D/wpa_supplicant( 1163): Add randomness: count=269 entropy=257
D/wpa_supplicant( 1163): Add randomness: count=270 entropy=258
D/wpa_supplicant( 1163): Add randomness: count=271 entropy=259
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_sup,plicant( 1163): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=272 entropy=260
D/wpa_supplicant( 1163): Add randomness: count=273 entropy=261
D/wpa_supplicant( 1163): Add randomness: count=274 entropy=262
D/wpa_supplicant( 1163): Add randomness: count=275 entropy=263
D/wpa_supplicant( 1163): Add randomness: count=276 entropy=264
D/wpa_supplicant( 1163): Add randomness: count=277 entropy=265
D/wpa_supplicant( 1163): Add randomness: count=278 entropy=266
D/wpa_supplicant( 1163): Add randomness: count=279 entropy=267
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1220) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000428655443
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
,I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000428655487
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000428655500
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000428655535
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000428655511
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====,
I/wpa_supplicant( 1163): id=12
I/wpa_supplicant( 1163): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-92
I/wpa_supplicant( 1163): tsf=0000000411215841
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=13
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000428655473
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=000000042865552
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 428655443, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 428655487, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 428655500, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 428655535, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 428655511, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -92, frequency: 2437, timestamp: 411215841, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 428655473, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 428655523, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 428655547, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-92], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(425f59a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425f59a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=280 entropy=268
D/wpa_supplicant( 1163): Add randomness: count=281 entropy=269
D/wpa_supplicant( 1163): Add randomness: count=282 entropy=270
D/wpa_supplicant( 1163): Add randomness: count=283 entropy=271
D/wpa_supplicant( 1163): Add randomness: count=284 entropy=272
D/wpa_supplicant( 1163): Add randomness: count=285 entropy=273
D/wpa_supplicant( 1163): Add randomness: count=286 entropy=274
D/wpa_supplicant( 1163): Add randomness: count=287 entropy=275
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
,I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=288 entropy=276
D/wpa_supplicant( 1163): Add randomness: count=289 entropy=277
D/wpa_supplicant( 1163): Add randomness: count=290 entropy=278
D/wpa_supplicant( 1163): Add randomness: count=291 entropy=279
D/wpa_supplicant( 1163): Add randomness: count=292 entropy=280
D/wpa_supplicant( 1163): Add randomness: count=293 entropy=281
D/wpa_supplicant( 1163): Add randomness: count=294 entropy=282
D/wpa_supplicant( 1163): Add randomness: count=295 entropy=283
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1074) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000445984458
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000445984504
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000445984517
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000445984540
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000445984528
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=13
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000445984490
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
,I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000445984552
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=15
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-91
I/wpa_supplicant( 1163): tsf=0000000445984568
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 445984458, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 445984504, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 445984517, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 445984540, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 445984528, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 445984490, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 445984552, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 445984568, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=296 entropy=284
D/wpa_supplicant( 1163): Add randomness: count=297 entropy=285
D/wpa_supplicant( 1163): Add randomness: count=298 entropy=286
D/wpa_supplicant( 1163): Add randomness: count=299 entropy=287
D/wpa_supplicant( 1163): Add randomness: count=300 entropy=288
D/wpa_supplicant( 1163): Add randomness: count=301 entropy=289
D/wpa_supplicant( 1163): Add randomness: count=302 entropy=290
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 w,api_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=303 entropy=291
D/wpa_supplicant( 1163): Add randomness: count=304 entropy=292
D/wpa_supplicant( 1163): Add randomness: count=305 entropy=293
D/wpa_supplicant( 1163): Add randomness: count=306 entropy=294
D/wpa_supplicant( 1163): Add randomness: count=307 entropy=295
D/wpa_supplicant( 1163): Add randomness: count=308 entropy=296
D/wpa_supplicant( 1163): Add randomness: count=309 entropy=297
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1163): reply (1074) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000463292787
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000463292832
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-80
I/wpa_supplicant( 1163): tsf=0000000445984517
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000463292856
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-85
I/wpa_supplicant( 1163): tsf=0000000445984528
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=13
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000463292818
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-88
I/wpa_supplicant( 1163): tsf=0000000463292868
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=15
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-91
I/wpa_supplicant( 1163): tsf=0000000463292883
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 463292787, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 463292832, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 445984517, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 463292856, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 445984528, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 463292818, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 463292868, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 463292883, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(43b0b428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b0b428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=310 entropy=298
D/wpa_supplicant( 1163): Add randomness: count=311 entropy=299
D/wpa_supplicant( 1163): Add randomness: count=312 entropy=300
D/wpa_supplicant( 1163): Add randomness: count=313 entropy=301
D/wpa_supplicant( 1163): Add randomness: count=314 entropy=302
D/wpa_supplicant( 1163): Add randomness: count=315 entropy=303
D/wpa_supplicant( 1163): Add randomness: count=316 entropy=304
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 06,:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=317 entropy=305
D/wpa_supplicant( 1163): Add randomness: count=318 entropy=306
D/wpa_supplicant( 1163): Add randomness: count=319 entropy=307
D/wpa_supplicant( 1163): Add randomness: count=320 entropy=308
D/wpa_supplicant( 1163): Add randomness: count=321 entropy=309
D/wpa_supplicant( 1163): Add randomness: count=322 entropy=310
D/wpa_supplicant( 1163): Add randomness: count=323 entropy=311
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  906): getDiscoveryDongleList
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1163): reply (1074) for get BSS: id=0,
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000480785578
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000480785605
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-80
I/wpa_supplicant( 1163): tsf=0000000480785616
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000480785635
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000480785645
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=13
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000463292818
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000480785625
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=15
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-91
I/wpa_supplicant( 1163): tsf=0000000480785656
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 480785578, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 480785605, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 480785616, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -86, frequency: 2437, timestamp: 480785635, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 480785645, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 463292818, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 480785625, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 480785656, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(430bff70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dc4d8: PendingIntentRecord{420e1940 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=486842, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(430bff70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42b0f018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42b0f018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=324 entropy=312
D/wpa_supplicant( 1163): Add randomness: count=325 entropy=313
D/wpa_supplicant( 1163): Add randomness: count=326 entropy=314
D/wpa_supplicant( 1163): Add randomness: count=327 entropy=315
D/wpa_supplicant( 1163): Add randomness: count=328 entropy=316
D/wpa_supplicant( 1163): Add randomness: count=329 entropy=317
D/wpa_supplicant( 1163): Add randomness: count=330 entropy=318
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 06,:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=331 entropy=319
D/wpa_supplicant( 1163): Add randomness: count=332 entropy=320
D/wpa_supplicant( 1163): Add randomness: count=333 entropy=321
D/wpa_supplicant( 1163): Add randomness: count=334 entropy=322
D/wpa_supplicant( 1163): Add randomness: count=335 entropy=323
D/wpa_supplicant( 1163): Add randomness: count=336 entropy=324
D/wpa_supplicant( 1163): Add randomness: count=337 entropy=325
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_su,pplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1108) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000498195456
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000498195483
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-83
I/wpa_supplicant( 1163): tsf=0000000498195494
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000498195524
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000498195513
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000498195503
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=15
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-91
I/wpa_supplicant( 1163): tsf=0000000480785656
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=16
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=24
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 498195456, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 498195483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 498195494, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -86, frequency: 2437, timestamp: 498195524, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 498195513, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 498195503, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 480785656, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 498195535, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList,
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] a0:c5:62:7a:49:96 freq=2412 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=338 entropy=326
D/wpa_supplicant( 1163): Add randomness: count=339 entropy=327
D/wpa_supplicant( 1163): Add randomness: count=340 entropy=328
D/wpa_supplicant( 1163): Add randomness: count=341 entropy=329
D/wpa_supplicant( 1163): Add randomness: count=342 entropy=330
D/wpa_supplicant( 1163): Add randomness: count=343 entropy=331
D/wpa_supplicant( 1163): Add randomness: count=344 entropy=332
D/wpa_supplicant( 1163): Add randomness: count=345 entropy=333
D/wpa_supplicant( 1163): Add randomness: count=346 entropy=334
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa,_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 8: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] a0:c5:62:7a:49:96 freq=2412 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=347 entropy=335
D/wpa_supplicant( 1163): Add randomness: count=348 entropy=336
D/wpa_supplicant( 1163): Add randomness: count=349 entropy=337
D/wpa_supplicant( 1163): Add randomness: count=350 entropy=338
D/wpa_supplicant( 1163): Add randomness: count=351 entropy=339
D/wpa_supplicant( 1163): Add randomness: count=352 entropy=340
D/wpa_supplicant( 1163): Add randomness: count=353 entropy=341
D/wpa_supplicant( 1163): Add randomness: count=354 entropy=342
D/wpa_supplicant( 1163): Add randomness: count=355 entropy=343
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1,163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1163): reply (1205) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000515641619
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000515641659
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-80
I/wpa_supplicant( 1163): tsf=0000000515641669
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000515641709
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000515641688
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000515641678
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=16
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000515641698
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=17
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=24
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 515641619, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 515641659, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 515641669, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -86, frequency: 2437, timestamp: 515641709, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 515641688, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 515641678, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, freque,ncy: 2437, timestamp: 515641698, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 7: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 515641647, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2412, timestamp: 515641718, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  92, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  82, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  67, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-90], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
,I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] a0:c5:62:7a:49:96 freq=2412 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=356 entropy=344
D/wpa_supplicant( 1163): Add randomness: count=357 entropy=345
D/wpa_supplicant( 1163): Add randomness: count=358 entropy=346
D/wpa_supplicant( 1163): Add randomness: count=359 entropy=347
D/wpa_supplicant( 1163): Add randomness: count=360 entropy=348
D/wpa_supplicant( 1163): Add randomness: count=361 entropy=349
D/wpa_supplicant( 1163): Add randomness: count=362 entropy=350
D/wpa_supplicant( 1163): Add randomness: count=363 entropy=351
D/wpa_supplicant( 1163): Add randomness: count=364 entropy=352
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
,D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
,I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1163): 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] a0:c5:62:7a:49:96 freq=2412 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
,D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=365 entropy=353
D/wpa_supplicant( 1163): Add randomness: count=366 entropy=354
D/wpa_supplicant( 1163): Add randomness: count=367 entropy=355
D/wpa_supplicant( 1163): Add randomness: count=368 entropy=356
D/wpa_supplicant( 1163): Add randomness: count=369 entropy=357
D/wpa_supplicant( 1163): Add randomness: count=370 entropy=358
D/wpa_supplicant( 1163): Add randomness: count=371 entropy=359
D/wpa_supplicant( 1163): Add randomness: count=372 entropy=360
D/wpa_supplicant( 1163): Add randomness: count=373 entropy=361
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1353) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000533095677
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000533095715
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-80
I/wpa_supplicant( 1163): tsf=0000000533095727
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000533095750
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000515641688
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698,
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000533095768
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=16
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000533095737
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=17
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=24
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 533095677, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 533095715, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 533095727, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -86, frequency: 2437, timestamp: 533095750, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 515641688, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 533095768, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 533095737, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 7: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 533095704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2412, timestamp: 533095759, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 9: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 533095778, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 10 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  92, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  82, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  67, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-90], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (10) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(439fe528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(439fe528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(435b0938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dc4d8: PendingIntentRecord{420e1940 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=546842, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435b0938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] a0:c5:62:7a:49:96 freq=2412 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=374 entropy=362
D/wpa_supplicant( 1163): Add randomness: count=375 entropy=363
D/wpa_supplicant( 1163): Add randomness: count=376 entropy=364
D/wpa_supplicant( 1163): Add randomness: count=377 entropy=365
D/wpa_supplicant( 1163): Add randomness: count=378 entropy=366
D/wpa_supplicant( 1163): Add randomness: count=379 entropy=367
D/wpa_supplicant( 1163): Add randomness: count=380 entropy=368
D/wpa_supplicant( 1163): Add randomness: count=381 entropy=369
D/wpa_supplicant( 1163): Add randomness: count=382 entropy=370
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1163): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1163): 6: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1163): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 8: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] a0:c5:62:7a:49:96 freq=2412 level=-90
,I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=383 entropy=371
D/wpa_supplicant( 1163): Add randomness: count=384 entropy=372
D/wpa_supplicant( 1163): Add randomness: count=385 entropy=373
D/wpa_supplicant( 1163): Add randomness: count=386 entropy=374
D/wpa_supplicant( 1163): Add randomness: count=387 entropy=375
,D/wpa_supplicant( 1163): Add randomness: count=388 entropy=376
D/wpa_supplicant( 1163): Add randomness: count=389 entropy=377
D/wpa_supplicant( 1163): Add randomness: count=390 entropy=378
D/wpa_supplicant( 1163): Add randomness: count=391 entropy=379
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
,I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1353) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000550535489
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000550535527
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-82
I/wpa_supplicant( 1163): tsf=0000000550535537
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000550535575
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000550535585
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000533095768
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supp,licant( 1163): id=16
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000533095737
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=17
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=24
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 550535489, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 550535527, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 550535537, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -86, frequency: 2437, timestamp: 550535575, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 550535585, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 533095768, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 533095737, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 550535515, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 8: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2412, timestamp: 550535545, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 9: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 550535555, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 10 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  92, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  82, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  67, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-90], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (10) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4366f458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4366f458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=392 entropy=380
D/wpa_supplicant( 1163): Add randomness: count=393 entropy=381
D/wpa_supplicant( 1163): Add randomness: count=394 entropy=382
D/wpa_supplicant( 1163): Add randomness: count=395 entropy=383
D/wpa_supplicant( 1163): Add randomness: count=396 entropy=384
D/wpa_supplicant( 1163): Add randomness: count=397 entropy=385
D/wpa_supplicant( 1163): Add randomness: count=398 entropy=386
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:1,1:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=399 entropy=387
D/wpa_supplicant( 1163): Add randomness: count=400 entropy=388
D/wpa_supplicant( 1163): Add randomness: count=401 entropy=389
D/wpa_supplicant( 1163): Add randomness: count=402 entropy=390
D/wpa_supplicant( 1163): Add randomness: count=403 entropy=391
D/wpa_supplicant( 1163): Add randomness: count=404 entropy=392
D/wpa_supplicant( 1163): Add randomness: count=405 entropy=393
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_sup,plicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1205) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000567954389
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000567954416
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000567954428
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000567954458
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000567954470
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000533095768
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=17
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000550535515
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====,
I/wpa_supplicant( 1163): id=18
I/wpa_supplicant( 1163): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000550535545
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 567954389, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 567954416, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 567954428, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 567954458, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 567954470, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 533095768, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 550535515, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 7: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2412, timestamp: 550535545, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 567954437, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 9 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  92, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  82, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  67, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-90], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter,
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=406 entropy=394
D/wpa_supplicant( 1163): Add randomness: count=407 entropy=395
D/wpa_supplicant( 1163): Add randomness: count=408 entropy=396
D/wpa_supplicant( 1163): Add randomness: count=409 entropy=397
D/wpa_supplicant( 1163): Add randomness: count=410 entropy=398
D/wpa_supplicant( 1163): Add randomness: count=411 entropy=399
D/wpa_supplicant( 1163): Add randomness: count=412 entropy=400
D/wpa_supplicant( 1163): Add randomness: count=413 entropy=401
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/,wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=414 entropy=402
D/wpa_supplicant( 1163): Add randomness: count=415 entropy=403
D/wpa_supplicant( 1163): Add randomness: count=416 entropy=404
D/wpa_supplicant( 1163): Add randomness: count=417 entropy=405
D/wpa_supplicant( 1163): Add randomness: count=418 entropy=406
D/wpa_supplicant( 1163): Add randomness: count=419 entropy=407
D/wpa_supplicant( 1163): Add randomness: count=420 entropy=408
D/wpa_supplicant( 1163): Add randomness: count=421 entropy=409
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1108) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000585422049
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000585422076
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000567954428
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000585422110
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000585422141
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000533095768
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=19
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000567954437
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=20
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=24
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 585422049, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 585422076, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 567954428, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 585422110, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 585422141, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 533095768, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 567954437, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 585422129, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 8 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(431b28d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(431b28d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=422 entropy=410
D/wpa_supplicant( 1163): Add randomness: count=423 entropy=411
D/wpa_supplicant( 1163): Add randomness: count=424 entropy=412
D/wpa_supplicant( 1163): Add randomness: count=425 entropy=413
D/wpa_supplicant( 1163): Add randomness: count=426 entropy=414
D/wpa_supplicant( 1163): Add randomness: count=427 entropy=415
D/wpa_supplicant( 1163): Add randomness: count=428 entropy=416
D/wpa_supplicant( 1163): Add randomness: count=429 entropy=417
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/,wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=430 entropy=418
D/wpa_supplicant( 1163): Add randomness: count=431 entropy=419
D/wpa_supplicant( 1163): Add randomness: count=432 entropy=420
D/wpa_supplicant( 1163): Add randomness: count=433 entropy=421
D/wpa_supplicant( 1163): Add randomness: count=434 entropy=422
D/wpa_supplicant( 1163): Add randomness: count=435 entropy=423
D/wpa_supplicant( 1163): Add randomness: count=436 entropy=424
D/wpa_supplicant( 1163): Add randomness: count=437 entropy=425
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1108) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000602835458
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55,
I/wpa_supplicant( 1163): tsf=0000000602835485
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000602835496
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000602835505
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000602835529
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000602835540
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=19
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000602835551
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=20
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=24
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 602835458, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 602835485, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 602835496, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 602835505, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 602835529, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 602835540, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 602835551, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 602835515, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43469d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dc4d8: PendingIntentRecord{420e1940 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=606842, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43469d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4361b7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4361b7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43556dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{424dd110: PendingIntentRecord{4405f5d0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=412788, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{42444d28: PendingIntentRecord{41f8b660 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452238510187, Int=0
,D/PMS     (  906): releaseWL(43556dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4120): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4120): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4120): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4120): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4120): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=438 entropy=426
D/wpa_supplicant( 1163): Add randomness: count=439 entropy=427
D/wpa_supplicant( 1163): Add randomness: count=440 entropy=428
D/wpa_supplicant( 1163): Add randomness: count=441 entropy=429
D/wpa_supplicant( 1163): Add randomness: count=442 entropy=430
D/wpa_supplicant( 1163): Add randomness: count=443 entropy=431
D/wpa_supplicant( 1163): Add randomness: count=444 entropy=432
D/wpa_supplicant( 1163): Add randomness: count=445 entropy=433
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/,wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=446 entropy=434
D/wpa_supplicant( 1163): Add randomness: count=447 entropy=435
D/wpa_supplicant( 1163): Add randomness: count=448 entropy=436
D/wpa_supplicant( 1163): Add randomness: count=449 entropy=437
D/wpa_supplicant( 1163): Add randomness: count=450 entropy=438
D/wpa_supplicant( 1163): Add randomness: count=451 entropy=439
D/wpa_supplicant( 1163): Add randomness: count=452 entropy=440
D/wpa_supplicant( 1163): Add randomness: count=453 entropy=441
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1108) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000620135544
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000620135571
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000620135583
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000620135592
,I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000620135635
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000620135612
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=19
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000620135622
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=20
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=24
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 620135544, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 620135571, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 620135583, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 620135592, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 620135635, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 620135612, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 620135622, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 620135601, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 8 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0,
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ContactMessageStore( 1247): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1247): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1247): sku_id=99
,D/ContactMessageStore( 1247): start background delete task...
,D/ContactMessageStore( 1247): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
,D/PMS     (  906): acquireWL(4404c860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{4250e5a0: PendingIntentRecord{43238978 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452238525414, Int=0
,D/PMS     (  906): releaseWL(4404c860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4120): [1] 5.onFinished: Installation state replication succeeded.
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=454 entropy=442
D/wpa_supplicant( 1163): Add randomness: count=455 entropy=443
D/wpa_supplicant( 1163): Add randomness: count=456 entropy=444
D/wpa_supplicant( 1163): Add randomness: count=457 entropy=445
D/wpa_supplicant( 1163): Add randomness: count=458 entropy=446
D/wpa_supplicant( 1163): Add randomness: count=459 entropy=447
D/wpa_supplicant( 1163): Add randomness: count=460 entropy=448
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: 38:f8:89:1,1:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=461 entropy=449
D/wpa_supplicant( 1163): Add randomness: count=462 entropy=450
D/wpa_supplicant( 1163): Add randomness: count=463 entropy=451
D/wpa_supplicant( 1163): Add randomness: count=464 entropy=452
D/wpa_supplicant( 1163): Add randomness: count=465 entropy=453
D/wpa_supplicant( 1163): Add randomness: count=466 entropy=454
D/wpa_supplicant( 1163): Add randomness: count=467 entropy=455
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_sup,plicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1108) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000637585892
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000637585919
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000637585932
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000637585964
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000637585973
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000620135612
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=19
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000637585942
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=20
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=24
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 637585892, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 637585919, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 637585932, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 637585964, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 637585973, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 620135612, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 637585942, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 620135601, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-86], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(41f30b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41f30b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1584): [EventService] reorderNotification, total:1
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1610): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/PowerUI ( 1118): closing low battery warning: level=98
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4758): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4176): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4176): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4176): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4176): Cust_ConnectToPC   : spcsc>false
,D/        ( 4176): Cust_ConnectToPC   : IPT>true
D/        ( 4176): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4176): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4176): Index of the first 1 = -1
W/Settings( 4176): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4176): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4176): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4176): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4176): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/ContextImpl( 4176): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4176): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1118): status:2 level:98 unsupport:false plugged:true
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=468 entropy=456
D/wpa_supplicant( 1163): Add randomness: count=469 entropy=457
D/wpa_supplicant( 1163): Add randomness: count=470 entropy=458
D/wpa_supplicant( 1163): Add randomness: count=471 entropy=459
D/wpa_supplicant( 1163): Add randomness: count=472 entropy=460
D/wpa_supplicant( 1163): Add randomness: count=473 entropy=461
D/wpa_supplicant( 1163): Add randomness: count=474 entropy=462
D/wpa_supplicant( 1163): Add randomness: count=475 entropy=463
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 9
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplic,ant( 1163): End print parameters
I/wpa_supplicant( 1163): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1163): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1163): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1163): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1163): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=476 entropy=464
D/wpa_supplicant( 1163): Add randomness: count=477 entropy=465
D/wpa_supplicant( 1163): Add randomness: count=478 entropy=466
D/wpa_supplicant( 1163): Add randomness: count=479 entropy=467
D/wpa_supplicant( 1163): Add randomness: count=480 entropy=468
,D/wpa_supplicant( 1163): Add randomness: count=481 entropy=469
D/wpa_supplicant( 1163): Add randomness: count=482 entropy=470
D/wpa_supplicant( 1163): Add randomness: count=483 entropy=471
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (1222) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-46
I/wpa_supplicant( 1163): tsf=0000000655001286
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-55
I/wpa_supplicant( 1163): tsf=0000000655001325
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-79
I/wpa_supplicant( 1163): tsf=0000000637585932
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=10
I/wpa_supplicant( 1163): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000637585964
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=11
I/wpa_supplicant( 1163): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000655001373
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC5999698
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=14
I/wpa_supplicant( 1163): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-89
I/wpa_supplicant( 1163): tsf=0000000620135612
I/wpa_supplicant( 1163): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=UPC Wi-Free
,I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=19
I/wpa_supplicant( 1163): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1163): freq=2462
I/wpa_supplicant( 1163): level=-90
I/wpa_supplicant( 1163): tsf=0000000637585942
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC0990019
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=20
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=24
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 655001286, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 655001325, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 637585932, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 637585964, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 655001373, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 620135612, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 637585942, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 655001363, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 655001313, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 9 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (9) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)

```
